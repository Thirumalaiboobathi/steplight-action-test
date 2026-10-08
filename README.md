# steplight-action-test

Throwaway test repository for [Thirumalaiboobathi/steplight-check-action](https://github.com/Thirumalaiboobathi/steplight-check-action).

`.steplight/runs` holds two runs recorded by the Steplight demo agent: a clean one and a flight booking that was hijacked by a hidden prompt injection. The `test-steplight-action` workflow (run it manually) checks that the action passes the first, fails the second, honours `fail-on`, writes SARIF and JUnit files, and rejects path traversal.
