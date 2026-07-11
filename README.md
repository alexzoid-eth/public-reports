# Public Web3 Security Audit Reports

A curated collection of public web3 / smart contract security audit reports,
aggregated as git submodules pointing at the upstream repositories of audit
firms, contest platforms, and independent security researchers.

Full checkout size is roughly **28 GB**, so prefer selective initialization.

## Usage

```bash
# clone without submodule content (fast)
git clone https://github.com/alexzoid-eth/public-reports
cd public-reports

# initialize only the sources you need
git submodule update --init trailofbits spearbit sherlock

# ... or everything (~28 GB)
git submodule update --init

# bump a submodule to the latest upstream state
git submodule update --remote trailofbits
```

## Selection criteria

Sources discovered via the
[0xNazgul/Blockchain-Security-Audit-List](https://github.com/0xNazgul/Blockchain-Security-Audit-List)
were added only if the upstream repository:

1. contains actual audit / security-review report files (PDF or Markdown)
   stored in the repository itself — link-only portfolios were excluded;
2. covers web3 / blockchain security (smart contracts, DeFi, bridges,
   wallets, L1/L2, zk);
3. had report files added within the last 3 years (cutoff 2023-07-11).

## Sources

### Aggregators & incident databases

| Directory | Source | Upstream |
|---|---|---|
| `defihacklabs` | DeFiHackLabs (incident PoC reproductions) | [SunWeb3Sec/DeFiHackLabs](https://github.com/SunWeb3Sec/DeFiHackLabs) |
| `solodit` | Solodit (multi-firm report content) | [solodit/solodit_content](https://github.com/solodit/solodit_content) |

### Audit companies & platforms

| Directory | Source | Upstream |
|---|---|---|
| `0xguard` | 0xGuard | [0xGuard-com/audit-reports](https://github.com/0xGuard-com/audit-reports) |
| `abdk` | ABDK Consulting | [abdk-consulting/audits](https://github.com/abdk-consulting/audits) |
| `arbitraryexecution` | Arbitrary Execution | [arbitraryexecution/publications](https://github.com/arbitraryexecution/publications) |
| `bailsec` | Bail Security | [bailsec/BailSec](https://github.com/bailsec/BailSec) |
| `blocksec` | BlockSec | [blocksecteam/audit-reports](https://github.com/blocksecteam/audit-reports) |
| `cdsecurity` | CD Security | [CDSecurity/audits](https://github.com/CDSecurity/audits) |
| `certora` | Certora | [Certora/SecurityReports](https://github.com/Certora/SecurityReports) |
| `chainsafe` | ChainSafe | [ChainSafe/audits](https://github.com/ChainSafe/audits) |
| `clarity` | Clarity Alliance | [Clarity-Alliance/audits](https://github.com/Clarity-Alliance/audits) |
| `coinspect` | Coinspect | [coinspect/publications](https://github.com/coinspect/publications) |
| `credshields` | CredShields | [Credshields/audit-reports](https://github.com/Credshields/audit-reports) |
| `cyfrin` | Cyfrin | [Cyfrin/cyfrin-audit-reports](https://github.com/Cyfrin/cyfrin-audit-reports) |
| `cystack` | CyStack | [cystack/security-audit-reports](https://github.com/cystack/security-audit-reports) |
| `decurity` | Decurity | [Decurity/audits](https://github.com/Decurity/audits) |
| `dedaub` | Dedaub | [Dedaub/audits](https://github.com/Dedaub/audits) |
| `egis` | Egis Security | [Egis-Security/audits](https://github.com/Egis-Security/audits) |
| `exvul` | ExVul | [ExVul-Sec/AuditReport](https://github.com/ExVul-Sec/AuditReport) |
| `g0group` | G0 Group | [g0-group/Audits](https://github.com/g0-group/Audits) |
| `guardian` | Guardian Audits | [GuardianAudits/Audits](https://github.com/GuardianAudits/Audits) |
| `guardianlab` | Guardian Audits (Defender) | [GuardianAudits/DefenderAudits](https://github.com/GuardianAudits/DefenderAudits) |
| `halborn` | Halborn | [HalbornSecurity/PublicReports](https://github.com/HalbornSecurity/PublicReports) |
| `hexens` | Hexens | [Hexens/Smart-Contract-Review-Public-Reports](https://github.com/Hexens/Smart-Contract-Review-Public-Reports) |
| `inference` | Inference AG | [InferenceAG/ReportPublications](https://github.com/InferenceAG/ReportPublications) |
| `informal` | Informal Systems | [informalsystems/audits](https://github.com/informalsystems/audits) |
| `kalos` | KALOS | [kalos-xyz/Publications](https://github.com/kalos-xyz/Publications) |
| `matterlabs` | Matter Labs | [matter-labs-audits/reports](https://github.com/matter-labs-audits/reports) |
| `midgar` | Midgar | [midgar-audits/public-audits](https://github.com/midgar-audits/public-audits) |
| `mixbytes` | MixBytes | [mixbytes/audits_public](https://github.com/mixbytes/audits_public) |
| `nethermind` | Nethermind | [NethermindEth/PublicAuditReports](https://github.com/NethermindEth/PublicAuditReports) |
| `oaksecurity` | Oak Security | [oak-security/audit-reports](https://github.com/oak-security/audit-reports) |
| `oxorio` | Oxorio | [oxor-io/public_audits](https://github.com/oxor-io/public_audits) |
| `pashov` | Pashov Audit Group | [pashov/audits](https://github.com/pashov/audits) |
| `peckshield` | PeckShield | [peckshield/publications](https://github.com/peckshield/publications) |
| `pessimistic` | Pessimistic | [pessimistic-io/audits](https://github.com/pessimistic-io/audits) |
| `rapidlabs` | Rapid Labs | [rapidlabsfinance/reports](https://github.com/rapidlabsfinance/reports) |
| `rezolv` | Rezolv | [RezolvSolutions/Audits](https://github.com/RezolvSolutions/Audits) |
| `rugdog` | RugDog | [rugdognet/reports](https://github.com/rugdognet/reports) |
| `runtimeverification` | Runtime Verification | [runtimeverification/publications](https://github.com/runtimeverification/publications) |
| `sbsecurity` | SBSecurity | [SB-Security/audits](https://github.com/SB-Security/audits) |
| `sec3` | Sec3 | [sec3-service/reports](https://github.com/sec3-service/reports) |
| `shellboxes` | ShellBoxes | [shellboxes/public-audit-reports](https://github.com/shellboxes/public-audit-reports) |
| `sherlock` | Sherlock (contest platform) | [sherlock-protocol/sherlock-reports](https://github.com/sherlock-protocol/sherlock-reports) |
| `shieldify` | Shieldify | [shieldify-security/audits-portfolio](https://github.com/shieldify-security/audits-portfolio) |
| `sigp` | Sigma Prime | [sigp/public-audits](https://github.com/sigp/public-audits) |
| `slowmist` | SlowMist (reports under `open-report-V2/`) | [slowmist/Knowledge-Base](https://github.com/slowmist/Knowledge-Base) |
| `solidified` | Solidified | [solidified-platform/audits](https://github.com/solidified-platform/audits) |
| `solidproof` | SolidProof (largest source, ~3.4 GB) | [solidproof/Projects](https://github.com/solidproof/Projects) |
| `spearbit` | Spearbit | [spearbit/portfolio](https://github.com/spearbit/portfolio) |
| `statemind` | Statemind | [statemindio/public-audits](https://github.com/statemindio/public-audits) |
| `techaudit` | Tech Audit | [Tech-Audit/Smart-Contract-Audits](https://github.com/Tech-Audit/Smart-Contract-Audits) |
| `trailofbits` | Trail of Bits | [trailofbits/publications](https://github.com/trailofbits/publications) |
| `truscova` | Truscova | [Truscova/Reports](https://github.com/Truscova/Reports) |
| `verichains` | Verichains | [verichains/public-audit-reports](https://github.com/verichains/public-audit-reports) |
| `yacademy` | yAcademy (yAudit fellowship) | [yAudit/fellowship-audits](https://github.com/yAudit/fellowship-audits) |
| `yaudit` | yAudit | [yAudit/reports](https://github.com/yAudit/reports) |
| `zealynx` | Zealynx | [ZealynxSecurity/Zealynx](https://github.com/ZealynxSecurity/Zealynx) |
| `zellic` | Zellic | [Zellic/publications](https://github.com/Zellic/publications) |
| `zokyo` | Zokyo | [zokyo-sec/audit-reports](https://github.com/zokyo-sec/audit-reports) |

### Solo auditors

| Directory | Source | Upstream |
|---|---|---|
| `abarbatei` | ABA (abarbatei) | [abarbatei/audits](https://github.com/abarbatei/audits) |
| `akshaysrivastav` | Akshay Srivastav | [akshaysrivastav/audits](https://github.com/akshaysrivastav/audits) |
| `frankcastle` | Frank Castle | [Frankcastleauditor/public-audits](https://github.com/Frankcastleauditor/public-audits) |
| `jakubheba` | Jakub Heba | [jakub-heba/portfolio](https://github.com/jakub-heba/portfolio) |
| `marchev` | Martin Marchev | [marchev/security-reviews](https://github.com/marchev/security-reviews) |
| `milotruck` | MiloTruck | [MiloTruck/audits](https://github.com/MiloTruck/audits) |
| `romeroadrian` | Adrian Romero | [romeroadrian/audits](https://github.com/romeroadrian/audits) |
| `sparkware` | Sparkware (JeffCX) | [JeffCX/Sparkware-audit-portfolio](https://github.com/JeffCX/Sparkware-audit-portfolio) |
| `windhustler` | GiuseppeDeLaZara (windhustler) | [windhustler/audits](https://github.com/windhustler/audits) |
| `zobront` | Zobront | [zobront/audits](https://github.com/zobront/audits) |

## Notes

- `pessimistic` upstream contains file paths that differ only by letter case,
  which permanently shows as modified content on case-insensitive filesystems
  (macOS/Windows). The submodule is configured with `ignore = dirty`.
- Contest platforms with per-contest repositories (Code4rena, Secure3) are not
  included here; Code4rena findings are tracked separately outside this repo.
