# Software Supply Chain Attack Vectors 

_(in construction...)_


| Ticketing System Access                      | Access Techniques           | Pipeline Posture                     | Code Security posture          |
| ---------------------------------------------| ----------------------------| -------------------------------------| -------------------------------|
|_Techniques (3)_                              | _Techniques (1)_              | _Techniques (10)_                      | _Techniques (6)_                 |
|Password in the ticketing system           | Missing 2FA                 | Admin/repo admin                     | Code security(Sast)            |
|2FA                                         |                             | inacive admins                       | Open source vulnerability(SCA) |
|'Wiki edit limited'                            |                             | No active admin                      | Keys & Crypto                  |
|                                              |                             | Inactive mainainers                  | Sanitization                   |
| Category (Stage in the supply chane)         |                             | inactive colaborators                | Logical errors                 |
| Line item cluster of attacks                 |                             | missing 2FA                          | DOS                            |
| Criterias                                    |                             | Force outside colaborators 2FA       |                                |
|                                              |                             | Main branch code review requirements |                                |
|                                              |                             | Secret exposed in build log          |                                |
|                                              |                             | ByPass approvers                     |                                |
|                                              |                             |                                      |                                |

| Reliance on Public Code Repos                | API                         | Artifactory                          | Containers                     |
| ---------------------------------------------| ----------------------------| -------------------------------------| -------------------------------|
| _Techniques (2)_                               | _Techniques (0)_              | _Techniques (0)_                      | _Techniques (3)_                 |
| Typosquatting                                |                             |                                      | Control plane                  |
| Package take over (BitGo)                    |                             |                                      | OS vulnereabilities            |
|                                              |                             |                                      |                                | 

| CI/CD Posture                                | Extensions                  | Clouds                               |                                |
| ---------------------------------------------| ----------------------------| -------------------------------------| -------------------------------|
| _Techniques (9)_                               | _Techniques (0)_              | _Techniques (0)_                       |                                |
| Review BYPass                                |                             |                                      |                                |
| Pipeline confusion.                          |                             |                                      |                                |
| Unofficial docker images runner              |                             |                                      |                                |
| Secrets in CI YAML                           |                             |                                      |                                |
| Echo secrets in Console                      |                             |                                      |                                |
| Code owners                                  |                             |                                      |                                |
| Commadn injection via context argument       |                             |                                      |                                |
| Preventing GitHub Actions from approving PR  |                             |                                      |                                |
| Limit permissions of GitHubToken             |                             |                                      |                                | 

