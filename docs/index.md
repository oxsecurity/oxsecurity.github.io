# OX Security Index

_(in construction...)_


                                             ## Software Supply Chain Attack Vectors 

| Ticketing System Access                      | Access Techniques           | Pipeline Posture                     | Code Security posture          |
| ---------------------------------------------| ----------------------------| -------------------------------------| -------------------------------|
| Techniques (3)                               | Techniques (1)              | Techniques (10)                      | Techniques (6)                 |
| Password in the ticketing system             | Missing 2FA                 | Admin/repo admin                     | Code security(Sast)            |
| 2FA                                          |                             | inacive admins                       | Open source vulnerability(SCA) |
| Wiki edit limited                            |                             | No active admin                      | Keys & Crypto                  |
|                                              |                             | Inactive mainainers                  | Sanitization                   |
| Category (Stage in the supply chane)         |                             | inactive colaborators                | Logical errors                 |
| Line item cluster of attacks                 |                             | missing 2FA                          | DOS                            |
| Criterias                                    |                             | Force outside colaborators 2FA       |                                |
|                                              |                             | Main branch code review requirements |                                |
|                                              |                             | Secret exposed in build log          |                                |
|                                              |                             | ByPass approvers                     |                                |
|                                              |                             |                                      |                                |
|                                              |                             |                                      |                                |
| Reliance on Public Code Repos                | API                         | Artifactory                          | Containers                     |
| Techniques (2)                               | Techniques (0)              | Techniques (0)                       | Techniques (3)                 |
| Typosquatting                                |                             |                                      | Control plane                  |
| Package take over (BitGo)                    |                             |                                      | OS vulnereabilities            |
|                                              |                             |                                      |                                | 
|                                              |                             |                                      |                                |
| CI/CD Posture                                | Extensions                  | Clouds                               |                                |
| Techniques (9)                               | Techniques (0)              | Techniques (0)                       |                                |
| Review BYPass                                |                             |                                      |                                |
| Pipeline confusion.                          |                             |                                      |                                |
| Unofficial docker images runner              |                             |                                      |                                |
| Secrets in CI YAML                           |                             |                                      |                                |
| Echo secrets in Console                      |                             |                                      |                                |
| Code owners                                  |                             |                                      |                                |
| Commadn injection via context argument       |                             |                                      |                                |
| Preventing GitHub Actions from approving PR  |                             |                                      |                                |
| Limit permissions of GitHubToken             |                             |                                      |                                | 


[LABEL](page)
<div class="twitter-card">
  <a class="twitter-timeline" href="https://twitter.com/nvuillam?ref_src=twsrc%5Etfw" data-theme="light" data-height="388">Tweets by MITREattack</a>
  <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
</div>
