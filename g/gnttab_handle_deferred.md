# Function: <code>gnttab_handle_deferred</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void gnttab_handle_deferred(long unsigned int unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff814c5230)
Location: drivers/xen/grant-table.c:310
Inline: False
```
**Symbols:**

```
ffffffff814c5230-ffffffff814c541a: gnttab_handle_deferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void gnttab_handle_deferred(long unsigned int unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815159b0)
Location: drivers/xen/grant-table.c:309
Inline: False
```
**Symbols:**

```
ffffffff815159b0-ffffffff81515b93: gnttab_handle_deferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void gnttab_handle_deferred(long unsigned int unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81541e40)
Location: drivers/xen/grant-table.c:309
Inline: False
```
**Symbols:**

```
ffffffff81541e40-ffffffff8154201f: gnttab_handle_deferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void gnttab_handle_deferred(long unsigned int unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81555c80)
Location: drivers/xen/grant-table.c:310
Inline: False
```
**Symbols:**

```
ffffffff81555c80-ffffffff81555e5f: gnttab_handle_deferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void gnttab_handle_deferred(struct timer_list *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815b98d0)
Location: drivers/xen/grant-table.c:364
Inline: False
```
**Symbols:**

```
ffffffff815b98d0-ffffffff815b9ab5: gnttab_handle_deferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void gnttab_handle_deferred(struct timer_list *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:364
Inline: False
```
**Symbols:**

```
ffffffff815f24a0-ffffffff815f26b1: gnttab_handle_deferred (STB_LOCAL)
ffffffff815f341a-ffffffff815f3444: gnttab_handle_deferred.cold.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void gnttab_handle_deferred(struct timer_list *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:368
Inline: False
```
**Symbols:**

```
ffffffff8160da90-ffffffff8160dca1: gnttab_handle_deferred (STB_LOCAL)
ffffffff8160e4b6-ffffffff8160e4e0: gnttab_handle_deferred.cold.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void gnttab_handle_deferred(struct timer_list *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:368
Inline: False
```
**Symbols:**

```
ffffffff81641c30-ffffffff81641e51: gnttab_handle_deferred (STB_LOCAL)
ffffffff8164224a-ffffffff81642276: gnttab_handle_deferred.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void gnttab_handle_deferred(struct timer_list *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:368
Inline: False
```
**Symbols:**

```
ffffffff816641f0-ffffffff81664411: gnttab_handle_deferred (STB_LOCAL)
ffffffff81664808-ffffffff81664834: gnttab_handle_deferred.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void gnttab_handle_deferred(struct timer_list *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:367
Inline: False
```
**Symbols:**

```
ffffffff817131a0-ffffffff817133c3: gnttab_handle_deferred (STB_LOCAL)
ffffffff81713df2-ffffffff81713e1e: gnttab_handle_deferred.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void gnttab_handle_deferred(struct timer_list *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:367
Inline: False
```
**Symbols:**

```
ffffffff817300a0-ffffffff817302c0: gnttab_handle_deferred (STB_LOCAL)
ffffffff81c04bfe-ffffffff81c04c2a: gnttab_handle_deferred.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void gnttab_handle_deferred(struct timer_list *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:367
Inline: False
```
**Symbols:**

```
ffffffff81713af0-ffffffff81713d10: gnttab_handle_deferred (STB_LOCAL)
ffffffff81bf6831-ffffffff81bf685d: gnttab_handle_deferred.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void gnttab_handle_deferred(struct timer_list *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:358
Inline: False
```
**Symbols:**

```
ffffffff81790520-ffffffff8179073a: gnttab_handle_deferred (STB_LOCAL)
ffffffff81cf5366-ffffffff81cf5397: gnttab_handle_deferred.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void gnttab_handle_deferred(struct timer_list *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:501
Inline: False
```
**Symbols:**

```
ffffffff818c8c40-ffffffff818c8ed5: gnttab_handle_deferred (STB_LOCAL)
ffffffff81ebd54a-ffffffff81ebd55f: gnttab_handle_deferred.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gnttab_handle_deferred(struct timer_list *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a19fc0)
Location: drivers/xen/grant-table.c:501
Inline: False
```
**Symbols:**

```
ffffffff81a19fc0-ffffffff81a1a26d: gnttab_handle_deferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gnttab_handle_deferred(struct timer_list *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a62ac0)
Location: drivers/xen/grant-table.c:506
Inline: False
```
**Symbols:**

```
ffffffff81a62ac0-ffffffff81a62e02: gnttab_handle_deferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gnttab_handle_deferred(struct timer_list *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81ab50f0)
Location: drivers/xen/grant-table.c:504
Inline: False
```
**Symbols:**

```
ffffffff81ab50f0-ffffffff81ab542f: gnttab_handle_deferred (STB_LOCAL)
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
void gnttab_handle_deferred(struct timer_list *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffff80001082e018)
Location: drivers/xen/grant-table.c:368
Inline: False
```
**Symbols:**

```
ffff80001082e018-ffff80001082e2fc: gnttab_handle_deferred (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void gnttab_handle_deferred(struct timer_list *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:368
Inline: False
```
**Symbols:**

```
ffffffff8162a060-ffffffff8162a281: gnttab_handle_deferred (STB_LOCAL)
ffffffff8162a678-ffffffff8162a6a4: gnttab_handle_deferred.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void gnttab_handle_deferred(struct timer_list *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:368
Inline: False
```
**Symbols:**

```
ffffffff81658030-ffffffff81658251: gnttab_handle_deferred (STB_LOCAL)
ffffffff81658648-ffffffff81658674: gnttab_handle_deferred.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void gnttab_handle_deferred(struct timer_list *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:368
Inline: False
```
**Symbols:**

```
ffffffff81672630-ffffffff81672851: gnttab_handle_deferred (STB_LOCAL)
ffffffff81672c48-ffffffff81672c74: gnttab_handle_deferred.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int unused</code> ➡️ <code>struct timer_list *unused</code>
</li>
</ul>
</details>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
