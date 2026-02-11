# Family Chore List

Simple tablet-friendly chore tracker for browser use on your Raspberry Pi.

## Run

From this folder:

```bash
python3 -m http.server 8002
```

Then open:

```text
http://<your-rpi-ip>:8002
```

## Notes

- Chore checkbox state is saved in the browser (local storage).
- `Reset for New Day` clears all checked chores.
- Edit `chores.json` to change chore titles, items, or columns without editing HTML.
