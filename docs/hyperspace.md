# Hyperspace Chess — Official Rules

*A strategic variant of classical chess that introduces hyperspace mechanics — allowing certain pieces to phase out of play and rematerialize on a secretly chosen square. The game emphasizes timing, commitment, and psychological foresight while preserving fair, deterministic play.*

---

## 1. Overview

* Hyperspace Chess is played using the standard board and pieces.
* All standard rules of chess apply **except where explicitly modified**.
* Eligible pieces may be removed from the board temporarily and return later on a **secretly recorded square**, after a **publicly declared delay**.

---

## 2. Hyperspace Eligibility

* Any piece **except pawns and kings** may enter hyperspace.
* A piece may enter hyperspace **instead of making a normal move**.
* A player may have **any number** of pieces in hyperspace.
* **Only one piece per player** may be scheduled to rematerialize on any given turn.

---

## 3. Entering Hyperspace

To enter hyperspace, the player must:

1. **Publically declare**:

   * The **type and square** of the piece being phased out (e.g., “bishop from c1”).
   * The **number of full future turns** (**N ≥ 1**) the piece will remain off the board.

2. Then:

   * **Remove the piece** from the board.
   * **Privately and immediately record** the **exact square** where the piece will rematerialize.

> The square must be valid for the piece (e.g., bishops must return to the correct color square).
> The reentry square and delay are **binding**, unless corrected due to an illegal situation (see Section 6).

---

## 4. Duration in Hyperspace

* The **turn of phasing out** does **not count** toward the delay.
* The **turn of rematerialization** also does **not count**.
* The piece remains off the board for **N full turns** of the player’s own color.
* It **returns at the end** of the player’s **(N+1)th turn**, after their regular move.

---

## 5. Rematerialization

* The piece reappears on its **secretly recorded square**.
* Only **one piece per player** may return on a given turn.
* The returning piece is **immediately active** and may:

  * Give **check** or **contribute to checkmate**
  * Combine with the regular move to deliver **double threats** or **double check**
* It **may not move** that turn.

### Return Outcomes:

* **Empty square** → the piece returns successfully.
* **Occupied by a friendly piece** → player chooses which to keep; the other is removed.
* **Occupied by an enemy piece** → the returning piece is **lost**; no capture occurs.
* **Invalid square (e.g., bishop returning to wrong-colored square)** → the piece is **forfeited**.

---

## 6. Scheduling Rules

* Each player may have **only one of their own pieces** scheduled to return on a given turn.
* This is checked **at the time of hyperspace entry**.
* If a scheduling conflict is discovered **before the opponent moves**, the player may:

  * **Cancel** the hyperspace action entirely (subject to touch-move rules, if in effect), or
  * **Change the delay** to a legal future turn

> If not caught in time, the scheduling stands and **both pieces return on scheudle**, even if illegal under the rules.  

---

## 7. Recordkeeping and Refereeing

* Upon entry:

  * The **piece and delay** are **publicly declared**.
  * The **destination square** is **privately recorded**.
* These commitments are **binding** once the opponent has made their next move.

### Referee Guidelines:

* In formal games, referees should:

  * Know and track **all return squares and delays**
  * Enforce forfeiture of invalid rematerializations
  * Ensure return timing is legal
* Referees must **not disclose** reentry squares to either player under any circumstances.

---

## 8. Special Interactions

* Hyperspace pieces are not on the board:

  * They **do not threaten, defend, block, or count for check**
  * They **cannot be captured**
  * They **may not be used in castling**
* You **may** phase out pieces to clear a path for castling.
* A **rook in hyperspace** may not participate in castling.

---

## 9. Check, Checkmate, and Stalemate

* Standard rules apply, with the following additions:

  * A rematerializing piece may contribute to **check** or **checkmate**
  * **Double check** is possible via coordinated move + rematerialization
  * If a player has no legal moves:

    * **Stalemate** if not in check
    * **Checkmate** if in check

---

# Hyperspace Chess – FAQ

---

### Q1: How many pieces can a player have in hyperspace at once?
There is no limit to how many of your pieces may be in hyperspace simultaneously.
However, you may only phase one piece per turn, and only one of your own pieces may be scheduled to return on any given turn.

---

### Q2: What exactly must I declare when phasing a piece into hyperspace?
You must publicly declare:

The type and square of the piece being phased

The number of full future turns (N ≥ 1) before it returns

The destination square is recorded privately and immediately, and may not be changed.

---

### Q3: What happens if two of my own pieces are scheduled to return on the same turn?
That’s illegal.
If caught before your opponent moves, you may either:

Cancel the phasing action, or

Adjust the return turn

If not caught in time, both pieces return regardless — and any resulting conflicts are resolved per the rules.

---

### Q4: Can my reentering piece give check or contribute to checkmate?
Yes. A piece that returns at the end of your turn becomes immediately active:

It can threaten, defend, give check, and participate in tactics

It cannot move until your next turn

---

### Q5: Can I move and have a piece return on the same turn?
Yes. A reentry does not replace your move — it happens after your normal action, at the end of your turn.

---

### Q6: What happens if the reentry square is occupied?
Occupied by enemy → Your piece is lost; no capture occurs.

Occupied by friendly piece → You must choose one to keep; the other is removed.

Invalid square (e.g., wrong color for a bishop) → Returning piece is forfeited.

---

### Q7: Can I use hyperspace to aid castling?
Yes, indirectly:

You may phase out a piece blocking the castling path

But a rook in hyperspace cannot be used for castling

---

### Q8: What happens if I have no legal move but still have phased pieces?
If your king is not in check and you have no legal moves (including no immediate reentries), it is stalemate, even if pieces are scheduled to return in future turns.

---

### Q9: Is it legal to phase a piece that is under attack?
Yes — hyperspace may be used to rescue an endangered piece, though doing so costs tempo and risks the reentry being blocked or lost.

---
### Q10: Can I bluff or fake my reentry square?

No — the destination square is a binding, privately recorded commitment made at the time of phasing.
In tournament play, a referee will enforce it.
