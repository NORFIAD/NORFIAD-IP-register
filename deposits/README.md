# Deposits

Each folder represents a registered intellectual property deposit.

## Structure

- **description.md** — Public description of the deposit
- **[ID].ots** — OpenTimestamps proof for original deposit

## Additions

New findings related to existing IP are added to the same folder:
- Each addition gets its own file and OTS proof
- Original deposit remains unchanged
- Additions reference the original but do not modify it

## Verification

Download the OTS file and verify at [OpenTimestamps.org](https://opentimestamps.org)
