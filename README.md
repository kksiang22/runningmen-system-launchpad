# RunningMen System Launchpad

A simple internal launchpad for staff to access company systems.

## Systems included

- AP: https://ap.runningmen.my
- Claims: https://claims.runningmen.my
- 4D: https://4d.runningmen.my
- Chingchong: https://chingchong.runningmen.my

## Local run

```bash
npm install
npm start
```

Then open:

```text
http://localhost:9090
```

## Railway deployment

Railway will still use `process.env.PORT` automatically, so this is safe for Railway.

Start command:

```bash
npm start
```

## Notes

No SSO. No database. No shared login.
Each card opens the target system in a new tab.
