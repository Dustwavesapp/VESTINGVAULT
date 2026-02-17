Vesting Vault
Token vesting with cliff + linear unlock. Supports SPL tokens, multi-beneficiary, on-chain revoke authority.
Implement a Vesting Vault program that:

Accepts SPL tokens into a vault account.

Supports configurable:

Start timestamp

Cliff duration

Total vesting duration

Total allocation

Releases tokens linearly after the cliff.

Allows beneficiaries to claim only accrued amounts.

Prevents over-claiming through precise on-chain accounting.

Supports multiple beneficiaries with isolated vesting schedules.

Includes an optional revoke authority capable of halting future vesting and reclaiming unvested tokens.

Enforces strict overflow checks and timestamp validation.

The implementation must follow Solana best practices, maintain rent exemption where required, and ensure full on-chain verifiability.
