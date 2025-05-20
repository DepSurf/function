# Function: <code>gnttab_request_version</code>

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
In drivers/xen/grant-table.c (ffffffff814c5716)
Location: drivers/xen/grant-table.c:1025
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_resume
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
In drivers/xen/grant-table.c (ffffffff81515c76)
Location: drivers/xen/grant-table.c:1024
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_resume
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
In drivers/xen/grant-table.c (ffffffff815420f6)
Location: drivers/xen/grant-table.c:1024
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_resume
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
In drivers/xen/grant-table.c (ffffffff81556086)
Location: drivers/xen/grant-table.c:1025
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void gnttab_request_version();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815ba640)
Location: drivers/xen/grant-table.c:1204
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_resume
```
**Symbols:**

```
ffffffff815ba640-ffffffff815ba7ef: gnttab_request_version (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gnttab_request_version();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1204
Inline: True
Direct callers:
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_resume
```
**Symbols:**

```
ffffffff815f2340-ffffffff815f2494: gnttab_request_version (STB_LOCAL)
ffffffff815f33c3-ffffffff815f341a: gnttab_request_version.cold.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gnttab_request_version();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8160e466)
Location: drivers/xen/grant-table.c:1332
Inline: True
Direct callers:
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_resume
```
**Symbols:**

```
ffffffff8160d830-ffffffff8160d984: gnttab_request_version (STB_LOCAL)
ffffffff8160e45f-ffffffff8160e4b6: gnttab_request_version.cold.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gnttab_request_version();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81642180)
Location: drivers/xen/grant-table.c:1332
Inline: True
Direct callers:
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_resume
```
**Symbols:**

```
ffffffff81641290-ffffffff816413db: gnttab_request_version (STB_LOCAL)
ffffffff81642179-ffffffff816421d0: gnttab_request_version.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gnttab_request_version();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8166473e)
Location: drivers/xen/grant-table.c:1332
Inline: True
Direct callers:
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_resume
```
**Symbols:**

```
ffffffff81663c50-ffffffff81663d9b: gnttab_request_version (STB_LOCAL)
ffffffff81664737-ffffffff8166478e: gnttab_request_version.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void gnttab_request_version();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1329
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_resume
```
**Symbols:**

```
ffffffff81712fd0-ffffffff8171302d: gnttab_request_version (STB_LOCAL)
ffffffff81713d5e-ffffffff81713da8: gnttab_request_version.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void gnttab_request_version();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1452
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_resume
```
**Symbols:**

```
ffffffff8172fdd0-ffffffff8172fe2d: gnttab_request_version (STB_LOCAL)
ffffffff81c04b6a-ffffffff81c04bb4: gnttab_request_version.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void gnttab_request_version();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1452
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_resume
```
**Symbols:**

```
ffffffff81713d10-ffffffff81713e57: gnttab_request_version (STB_LOCAL)
ffffffff81bf685d-ffffffff81bf68b4: gnttab_request_version.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void gnttab_request_version();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1459
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_resume
```
**Symbols:**

```
ffffffff81790740-ffffffff81790887: gnttab_request_version (STB_LOCAL)
ffffffff81cf5397-ffffffff81cf53ee: gnttab_request_version.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gnttab_request_version();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81ebd4e0)
Location: drivers/xen/grant-table.c:1523
Inline: True
Direct callers:
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_resume
```
**Symbols:**

```
ffffffff818c89f0-ffffffff818c8b6e: gnttab_request_version (STB_LOCAL)
ffffffff81ebd4d9-ffffffff81ebd54a: gnttab_request_version.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gnttab_request_version();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a19750)
Location: drivers/xen/grant-table.c:1526
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_resume
```
**Symbols:**

```
ffffffff81a19750-ffffffff81a1993b: gnttab_request_version (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gnttab_request_version();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a627d0)
Location: drivers/xen/grant-table.c:1544
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_resume
```
**Symbols:**

```
ffffffff81a627d0-ffffffff81a629bb: gnttab_request_version (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gnttab_request_version();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81ab5730)
Location: drivers/xen/grant-table.c:1542
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_resume
```
**Symbols:**

```
ffffffff81ab5730-ffffffff81ab591b: gnttab_request_version (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void gnttab_request_version();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffff80001082bf68)
Location: drivers/xen/grant-table.c:1332
Inline: True
Direct callers:
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_resume
```
**Symbols:**

```
ffff80001082bf68-ffff80001082c028: gnttab_request_version (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gnttab_request_version();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8162a5ae)
Location: drivers/xen/grant-table.c:1332
Inline: True
Direct callers:
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_resume
```
**Symbols:**

```
ffffffff81629ac0-ffffffff81629c0b: gnttab_request_version (STB_LOCAL)
ffffffff8162a5a7-ffffffff8162a5fe: gnttab_request_version.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gnttab_request_version();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8165857e)
Location: drivers/xen/grant-table.c:1332
Inline: True
Direct callers:
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_resume
```
**Symbols:**

```
ffffffff81657a90-ffffffff81657bdb: gnttab_request_version (STB_LOCAL)
ffffffff81658577-ffffffff816585ce: gnttab_request_version.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gnttab_request_version();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81672b7e)
Location: drivers/xen/grant-table.c:1332
Inline: True
Direct callers:
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_resume
```
**Symbols:**

```
ffffffff81672090-ffffffff816721db: gnttab_request_version (STB_LOCAL)
ffffffff81672b77-ffffffff81672bce: gnttab_request_version.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
