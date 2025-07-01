
# Hyperspace Chess — Official Rules v2.3

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

  * **Cancel** the hyperspace action entirely, or
  * **Change the delay** to a legal future turn

> If not caught in time, the scheduling stands and **both pieces return**, even if illegal under the rules.

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

### Q1: What must I declare when entering hyperspace?

* The **piece and square** being removed
* The **number of full future turns (N)** it will remain off the board

---

### Q2: What is kept secret?

Only the **destination square**, which is privately recorded and may not be changed (unless corrected immediately due to illegal scheduling).

---

### Q3: Can both players have a piece return on the same turn?

Yes. The one-return-per-turn rule applies **per player**, not globally.

---

### Q4: Can I schedule two of my own pieces to return on the same turn?

No. That is illegal.

* If caught **before the opponent moves**, you may **adjust the delay** or **cancel** the hyperspace action.
* If **not caught in time**, **both pieces return** and the move stands.

---

### Q5: Can I change the delay after declaring it?

Only to correct a scheduling conflict **before the opponent’s next move**.
Once the opponent moves, the commitment is locked in.

---

### Q6: Can a returning piece give check or checkmate?

Yes — the piece becomes **immediately active** at the end of the turn it returns.

---

### Q7: Can I move and rematerialize on the same turn?

Yes — the regular move occurs first; then the rematerializing piece returns.

---

### Q8: Can I move the rematerializing piece that turn?

No — it **may not move** until your next turn, but it may **threaten, check**, and **defend** immediately.

---

### Q9: What happens if the return square is occupied?

* **By a friendly piece** → choose which to keep
* **By an enemy piece** → returning piece is **lost**
* **By an invalid square (e.g., bishop on wrong color)** → piece is **forfeited**

---

### Q10: Can I use hyperspace to enable castling?

Yes — phasing out a blocking piece is legal.
But the rook itself **cannot be in hyperspace** and still castle.

---

### Q11: What are the risks of longer delays?

You’re temporarily **down material**, and your reentry square may become **occupied** or **tactically exposed** by the time it’s used.

---

### Q12: Can a referee see the secret reentry squares?

Yes — referees are responsible for tracking all private commitments.
They must **never reveal** destination squares to either player.

---

### Q13: Can I force a stalemate with hyperspace?

Yes — if your king is not in check and **all your other pieces are in hyperspace** with no legal move, it is a **valid stalemate**.

