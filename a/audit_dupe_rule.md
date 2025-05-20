# Function: <code>audit_dupe_rule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct audit_entry *audit_dupe_rule(struct audit_krule *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811242f0)
Location: kernel/auditfilter.c:782
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff811242f0-ffffffff811245da: audit_dupe_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct audit_entry *audit_dupe_rule(struct audit_krule *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8112c400)
Location: kernel/auditfilter.c:782
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff8112c400-ffffffff8112c6d7: audit_dupe_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct audit_entry *audit_dupe_rule(struct audit_krule *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81136110)
Location: kernel/auditfilter.c:784
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81136110-ffffffff811363e7: audit_dupe_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct audit_entry *audit_dupe_rule(struct audit_krule *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811373f0)
Location: kernel/auditfilter.c:784
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff811373f0-ffffffff811376d8: audit_dupe_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct audit_entry *audit_dupe_rule(struct audit_krule *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811440f0)
Location: kernel/auditfilter.c:803
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff811440f0-ffffffff811443d8: audit_dupe_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct audit_entry *audit_dupe_rule(struct audit_krule *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:802
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff8115441a-ffffffff8115442f: audit_dupe_rule.cold.18 (STB_LOCAL)
ffffffff81152ae0-ffffffff81152d7b: audit_dupe_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct audit_entry *audit_dupe_rule(struct audit_krule *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:800
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff8116123a-ffffffff8116124f: audit_dupe_rule.cold.18 (STB_LOCAL)
ffffffff8115f790-ffffffff8115fa23: audit_dupe_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct audit_entry *audit_dupe_rule(struct audit_krule *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:804
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff8116d92c-ffffffff8116d941: audit_dupe_rule.cold (STB_LOCAL)
ffffffff8116c660-ffffffff8116c938: audit_dupe_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct audit_entry *audit_dupe_rule(struct audit_krule *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:811
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff811797c4-ffffffff811797d9: audit_dupe_rule.cold (STB_LOCAL)
ffffffff811784e0-ffffffff811787b8: audit_dupe_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct audit_entry *audit_dupe_rule(struct audit_krule *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:812
Inline: False
Direct callers:
  - kernel/auditfilter.c:update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff8118c694-ffffffff8118c6a9: audit_dupe_rule.cold (STB_LOCAL)
ffffffff8118b7c0-ffffffff8118ba8a: audit_dupe_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct audit_entry *audit_dupe_rule(struct audit_krule *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:812
Inline: False
Direct callers:
  - kernel/auditfilter.c:update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81be4973-ffffffff81be4988: audit_dupe_rule.cold (STB_LOCAL)
ffffffff811889f0-ffffffff81188c9e: audit_dupe_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct audit_entry *audit_dupe_rule(struct audit_krule *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:812
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81bd67d4-ffffffff81bd67e9: audit_dupe_rule.cold (STB_LOCAL)
ffffffff81189970-ffffffff81189c1e: audit_dupe_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct audit_entry *audit_dupe_rule(struct audit_krule *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:812
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81cb353c-ffffffff81cb3552: audit_dupe_rule.cold (STB_LOCAL)
ffffffff811b2380-ffffffff811b265a: audit_dupe_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct audit_entry *audit_dupe_rule(struct audit_krule *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:819
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81e64371-ffffffff81e64387: audit_dupe_rule.cold (STB_LOCAL)
ffffffff811e4690-ffffffff811e49a0: audit_dupe_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct audit_entry *audit_dupe_rule(struct audit_krule *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8122a660)
Location: kernel/auditfilter.c:819
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff8122a660-ffffffff8122a986: audit_dupe_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct audit_entry *audit_dupe_rule(struct audit_krule *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81240c40)
Location: kernel/auditfilter.c:819
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81240c40-ffffffff81240f67: audit_dupe_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct audit_entry *audit_dupe_rule(struct audit_krule *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8125aa60)
Location: kernel/auditfilter.c:820
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff8125aa60-ffffffff8125ad63: audit_dupe_rule (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct audit_entry *audit_dupe_rule(struct audit_krule *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffff8000101ed658)
Location: kernel/auditfilter.c:811
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffff8000101ed658-ffff8000101ed924: audit_dupe_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct audit_entry *audit_dupe_rule(struct audit_krule *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (c042d6f0)
Location: kernel/auditfilter.c:811
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
c042d6f0-c042d9e8: audit_dupe_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct audit_entry *audit_dupe_rule(struct audit_krule *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (c00000000025fe60)
Location: kernel/auditfilter.c:811
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
c00000000025fe60-c000000000260228: audit_dupe_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct audit_entry *audit_dupe_rule(struct audit_krule *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffe000161bd6)
Location: kernel/auditfilter.c:811
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffe000161bd6-ffffffe000161e56: audit_dupe_rule (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct audit_entry *audit_dupe_rule(struct audit_krule *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:811
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81171de4-ffffffff81171df9: audit_dupe_rule.cold (STB_LOCAL)
ffffffff81170b00-ffffffff81170dd8: audit_dupe_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct audit_entry *audit_dupe_rule(struct audit_krule *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:811
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81164f84-ffffffff81164f99: audit_dupe_rule.cold (STB_LOCAL)
ffffffff81163ca0-ffffffff81163f78: audit_dupe_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct audit_entry *audit_dupe_rule(struct audit_krule *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:811
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff8116fbb4-ffffffff8116fbc9: audit_dupe_rule.cold (STB_LOCAL)
ffffffff8116e8d0-ffffffff8116eba8: audit_dupe_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct audit_entry *audit_dupe_rule(struct audit_krule *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:811
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff8117d3b4-ffffffff8117d3c9: audit_dupe_rule.cold (STB_LOCAL)
ffffffff8117c0c0-ffffffff8117c398: audit_dupe_rule (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
