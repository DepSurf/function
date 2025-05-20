# Function: <code>vmstat_refresh</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vmstat_refresh(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811c71c0)
Location: mm/vmstat.c:1636
Inline: False
```
**Symbols:**

```
ffffffff811c71c0-ffffffff811c7278: vmstat_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vmstat_refresh(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811d72e0)
Location: mm/vmstat.c:1560
Inline: False
```
**Symbols:**

```
ffffffff811d72e0-ffffffff811d7398: vmstat_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vmstat_refresh(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811e0130)
Location: mm/vmstat.c:1577
Inline: False
```
**Symbols:**

```
ffffffff811e0130-ffffffff811e01c9: vmstat_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vmstat_refresh(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811f60e0)
Location: mm/vmstat.c:1784
Inline: False
```
**Symbols:**

```
ffffffff811f60e0-ffffffff811f61b3: vmstat_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int vmstat_refresh(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:1741
Inline: False
```
**Symbols:**

```
ffffffff812174a7-ffffffff812174eb: vmstat_refresh.cold.20 (STB_LOCAL)
ffffffff81217370-ffffffff8121740d: vmstat_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int vmstat_refresh(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:1743
Inline: False
```
**Symbols:**

```
ffffffff8122a3b7-ffffffff8122a3fb: vmstat_refresh.cold.20 (STB_LOCAL)
ffffffff8122a280-ffffffff8122a31d: vmstat_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int vmstat_refresh(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:1739
Inline: False
```
**Symbols:**

```
ffffffff8123a037-ffffffff8123a07f: vmstat_refresh.cold (STB_LOCAL)
ffffffff81239f10-ffffffff81239f9b: vmstat_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int vmstat_refresh(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:1758
Inline: False
```
**Symbols:**

```
ffffffff81248337-ffffffff8124837f: vmstat_refresh.cold (STB_LOCAL)
ffffffff81248210-ffffffff8124829b: vmstat_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int vmstat_refresh(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:1767
Inline: False
```
**Symbols:**

```
ffffffff812764c1-ffffffff81276509: vmstat_refresh.cold (STB_LOCAL)
ffffffff81276390-ffffffff8127641b: vmstat_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int vmstat_refresh(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:1810
Inline: False
```
**Symbols:**

```
ffffffff81be6f6c-ffffffff81be6fb4: vmstat_refresh.cold (STB_LOCAL)
ffffffff81280d40-ffffffff81280dcb: vmstat_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vmstat_refresh(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:1842
Inline: False
```
**Symbols:**

```
ffffffff81bd8d0c-ffffffff81bd8d5c: vmstat_refresh.cold (STB_LOCAL)
ffffffff81285e40-ffffffff81285ef3: vmstat_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vmstat_refresh(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:1849
Inline: False
```
**Symbols:**

```
ffffffff81cbab70-ffffffff81cbabc0: vmstat_refresh.cold (STB_LOCAL)
ffffffff812c5050-ffffffff812c5148: vmstat_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vmstat_refresh(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:1878
Inline: False
```
**Symbols:**

```
ffffffff81e6c48a-ffffffff81e6c4da: vmstat_refresh.cold (STB_LOCAL)
ffffffff813225d0-ffffffff813226dd: vmstat_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vmstat_refresh(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813967f0)
Location: mm/vmstat.c:1873
Inline: False
```
**Symbols:**

```
ffffffff813967f0-ffffffff81396939: vmstat_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vmstat_refresh(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813c9720)
Location: mm/vmstat.c:1883
Inline: False
```
**Symbols:**

```
ffffffff813c9720-ffffffff813c9873: vmstat_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vmstat_refresh(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813f40b0)
Location: mm/vmstat.c:1887
Inline: False
```
**Symbols:**

```
ffffffff813f40b0-ffffffff813f4201: vmstat_refresh (STB_GLOBAL)
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
int vmstat_refresh(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffff8000102dcc50)
Location: mm/vmstat.c:1758
Inline: False
```
**Symbols:**

```
ffff8000102dcc50-ffff8000102dcdac: vmstat_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vmstat_refresh(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c050270c)
Location: mm/vmstat.c:1758
Inline: False
```
**Symbols:**

```
c050270c-c05027c8: vmstat_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vmstat_refresh(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c00000000039c880)
Location: mm/vmstat.c:1758
Inline: False
```
**Symbols:**

```
c00000000039c880-c00000000039ca10: vmstat_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vmstat_refresh(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffe0001f5818)
Location: mm/vmstat.c:1758
Inline: False
```
**Symbols:**

```
ffffffe0001f5818-ffffffe0001f58d8: vmstat_refresh (STB_GLOBAL)
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
int vmstat_refresh(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:1758
Inline: False
```
**Symbols:**

```
ffffffff81240987-ffffffff812409cf: vmstat_refresh.cold (STB_LOCAL)
ffffffff81240860-ffffffff812408eb: vmstat_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int vmstat_refresh(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:1758
Inline: False
```
**Symbols:**

```
ffffffff81233987-ffffffff812339cf: vmstat_refresh.cold (STB_LOCAL)
ffffffff81233860-ffffffff812338eb: vmstat_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int vmstat_refresh(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:1758
Inline: False
```
**Symbols:**

```
ffffffff8123e727-ffffffff8123e76f: vmstat_refresh.cold (STB_LOCAL)
ffffffff8123e600-ffffffff8123e68b: vmstat_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int vmstat_refresh(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:1758
Inline: False
```
**Symbols:**

```
ffffffff8124de57-ffffffff8124de9f: vmstat_refresh.cold (STB_LOCAL)
ffffffff8124dd30-ffffffff8124ddbb: vmstat_refresh (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
