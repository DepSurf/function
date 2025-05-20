# Function: <code>audit_data_to_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81124759)
Location: kernel/auditfilter.c:419
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8112c856)
Location: kernel/auditfilter.c:419
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81136566)
Location: kernel/auditfilter.c:420
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81137856)
Location: kernel/auditfilter.c:420
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81144556)
Location: kernel/auditfilter.c:439
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81152f26)
Location: kernel/auditfilter.c:439
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8115fbd6)
Location: kernel/auditfilter.c:437
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct audit_entry *audit_data_to_entry(struct audit_rule_data *data, size_t datasz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:441
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff8116bd40-ffffffff8116c617: audit_data_to_entry (STB_LOCAL)
ffffffff8116d8ee-ffffffff8116d92c: audit_data_to_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct audit_entry *audit_data_to_entry(struct audit_rule_data *data, size_t datasz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:441
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff81177c20-ffffffff81178494: audit_data_to_entry (STB_LOCAL)
ffffffff8117978e-ffffffff811797c4: audit_data_to_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct audit_entry *audit_data_to_entry(struct audit_rule_data *data, size_t datasz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:441
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff8118b090-ffffffff8118b780: audit_data_to_entry (STB_LOCAL)
ffffffff8118c65e-ffffffff8118c694: audit_data_to_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct audit_entry *audit_data_to_entry(struct audit_rule_data *data, size_t datasz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:441
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff811882e0-ffffffff811889ae: audit_data_to_entry (STB_LOCAL)
ffffffff81be493d-ffffffff81be4973: audit_data_to_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct audit_entry *audit_data_to_entry(struct audit_rule_data *data, size_t datasz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:441
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff81189260-ffffffff8118992b: audit_data_to_entry (STB_LOCAL)
ffffffff81bd679e-ffffffff81bd67d4: audit_data_to_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct audit_entry *audit_data_to_entry(struct audit_rule_data *data, size_t datasz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:441
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff811b1af0-ffffffff811b22db: audit_data_to_entry (STB_LOCAL)
ffffffff81cb3506-ffffffff81cb353c: audit_data_to_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct audit_entry *audit_data_to_entry(struct audit_rule_data *data, size_t datasz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:449
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff811e3dd0-ffffffff811e45c4: audit_data_to_entry (STB_LOCAL)
ffffffff81e6433b-ffffffff81e64371: audit_data_to_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct audit_entry *audit_data_to_entry(struct audit_rule_data *data, size_t datasz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81229d50)
Location: kernel/auditfilter.c:449
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff81229d50-ffffffff8122a578: audit_data_to_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct audit_entry *audit_data_to_entry(struct audit_rule_data *data, size_t datasz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81240310)
Location: kernel/auditfilter.c:449
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff81240310-ffffffff81240b54: audit_data_to_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct audit_entry *audit_data_to_entry(struct audit_rule_data *data, size_t datasz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8125a180)
Location: kernel/auditfilter.c:449
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff8125a180-ffffffff8125a97f: audit_data_to_entry (STB_LOCAL)
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
struct audit_entry *audit_data_to_entry(struct audit_rule_data *data, size_t datasz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffff8000101ecde0)
Location: kernel/auditfilter.c:441
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffff8000101ecde0-ffff8000101ed5ec: audit_data_to_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct audit_entry *audit_data_to_entry(struct audit_rule_data *data, size_t datasz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (c042c9f8)
Location: kernel/auditfilter.c:441
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
c042c9f8-c042d690: audit_data_to_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct audit_entry *audit_data_to_entry(struct audit_rule_data *data, size_t datasz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (c00000000025eee0)
Location: kernel/auditfilter.c:441
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
c00000000025eee0-c00000000025fdec: audit_data_to_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct audit_entry *audit_data_to_entry(struct audit_rule_data *data, size_t datasz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffe0001614d6)
Location: kernel/auditfilter.c:441
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffe0001614d6-ffffffe000161b6e: audit_data_to_entry (STB_LOCAL)
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
struct audit_entry *audit_data_to_entry(struct audit_rule_data *data, size_t datasz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:441
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff81170240-ffffffff81170ab4: audit_data_to_entry (STB_LOCAL)
ffffffff81171dae-ffffffff81171de4: audit_data_to_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct audit_entry *audit_data_to_entry(struct audit_rule_data *data, size_t datasz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:441
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff811633e0-ffffffff81163c54: audit_data_to_entry (STB_LOCAL)
ffffffff81164f4e-ffffffff81164f84: audit_data_to_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct audit_entry *audit_data_to_entry(struct audit_rule_data *data, size_t datasz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:441
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff8116e010-ffffffff8116e884: audit_data_to_entry (STB_LOCAL)
ffffffff8116fb7e-ffffffff8116fbb4: audit_data_to_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct audit_entry *audit_data_to_entry(struct audit_rule_data *data, size_t datasz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:441
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff8117b800-ffffffff8117c074: audit_data_to_entry (STB_LOCAL)
ffffffff8117d37e-ffffffff8117d3b4: audit_data_to_entry.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
