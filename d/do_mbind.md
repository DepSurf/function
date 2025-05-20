# Function: <code>do_mbind</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int do_mbind(long unsigned int start, long unsigned int len, short unsigned int mode, short unsigned int mode_flags, nodemask_t *nmask, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811e24a0)
Location: mm/mempolicy.c:1135
Inline: False
Direct callers:
  - mm/mempolicy.c:compat_SyS_mbind
```
**Symbols:**

```
ffffffff811e24a0-ffffffff811e29e1: do_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int do_mbind(long unsigned int start, long unsigned int len, short unsigned int mode, short unsigned int mode_flags, nodemask_t *nmask, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81200e90)
Location: mm/mempolicy.c:1167
Inline: False
Direct callers:
  - mm/mempolicy.c:compat_SyS_mbind
```
**Symbols:**

```
ffffffff81200e90-ffffffff812013b6: do_mbind (STB_LOCAL)
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
In mm/mempolicy.c (ffffffff81212971)
Location: mm/mempolicy.c:1169
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_mbind
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
In mm/mempolicy.c (ffffffff8121dca1)
Location: mm/mempolicy.c:1098
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_mbind
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
In mm/mempolicy.c (ffffffff81238ef1)
Location: mm/mempolicy.c:1161
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_mbind
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
In mm/mempolicy.c (ffffffff8125c425)
Location: mm/mempolicy.c:1137
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
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
In mm/mempolicy.c (ffffffff81270d05)
Location: mm/mempolicy.c:1177
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128c318)
Location: mm/mempolicy.c:1216
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129bee8)
Location: mm/mempolicy.c:1217
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_mbind(long unsigned int start, long unsigned int len, short unsigned int mode, short unsigned int mode_flags, nodemask_t *nmask, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812cfcd0)
Location: mm/mempolicy.c:1286
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff812cfcd0-ffffffff812d008c: do_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_mbind(long unsigned int start, long unsigned int len, short unsigned int mode, short unsigned int mode_flags, nodemask_t *nmask, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812db7a0)
Location: mm/mempolicy.c:1266
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff812db7a0-ffffffff812dbbb0: do_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_mbind(long unsigned int start, long unsigned int len, short unsigned int mode, short unsigned int mode_flags, nodemask_t *nmask, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e3020)
Location: mm/mempolicy.c:1278
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff812e3020-ffffffff812e3428: do_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int do_mbind(long unsigned int start, long unsigned int len, short unsigned int mode, short unsigned int mode_flags, nodemask_t *nmask, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8132a380)
Location: mm/mempolicy.c:1249
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff8132a380-ffffffff8132a7ac: do_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int do_mbind(long unsigned int start, long unsigned int len, short unsigned int mode, short unsigned int mode_flags, nodemask_t *nmask, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81399cc0)
Location: mm/mempolicy.c:1242
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff81399cc0-ffffffff8139a0f7: do_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_mbind(long unsigned int start, long unsigned int len, short unsigned int mode, short unsigned int mode_flags, nodemask_t *nmask, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81419c70)
Location: mm/mempolicy.c:1257
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff81419c70-ffffffff8141a0c7: do_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int do_mbind(long unsigned int start, long unsigned int len, short unsigned int mode, short unsigned int mode_flags, nodemask_t *nmask, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8144d120)
Location: mm/mempolicy.c:1262
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff8144d120-ffffffff8144d65b: do_mbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int do_mbind(long unsigned int start, long unsigned int len, short unsigned int mode, short unsigned int mode_flags, nodemask_t *nmask, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (0)
Location: mm/mempolicy.c:1218
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff81486a20-ffffffff8148728b: do_mbind (STB_LOCAL)
ffffffff821c3bc1-ffffffff821c3be6: do_mbind.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffff80001033af00)
Location: mm/mempolicy.c:1217
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int do_mbind(long unsigned int start, long unsigned int len, short unsigned int mode, short unsigned int mode_flags, nodemask_t *nmask, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000415960)
Location: mm/mempolicy.c:1217
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
c000000000415960-c000000000416070: do_mbind (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812944c8)
Location: mm/mempolicy.c:1217
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812860d8)
Location: mm/mempolicy.c:1217
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812922d8)
Location: mm/mempolicy.c:1217
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812a20d0)
Location: mm/mempolicy.c:1217
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
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
</ul>
