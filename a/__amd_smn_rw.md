# Function: <code>__amd_smn_rw</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 *value, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81065ea0)
Location: arch/x86/kernel/amd_nb.c:92
Inline: False
Direct callers:
  - arch/x86/kernel/amd_nb.c:amd_smn_write
  - arch/x86/kernel/amd_nb.c:amd_smn_read
```
**Symbols:**

```
ffffffff81065ea0-ffffffff81065fac: __amd_smn_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 *value, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81065230)
Location: arch/x86/kernel/amd_nb.c:92
Inline: False
Direct callers:
  - arch/x86/kernel/amd_nb.c:amd_smn_write
  - arch/x86/kernel/amd_nb.c:amd_smn_read
```
**Symbols:**

```
ffffffff81065230-ffffffff8106531f: __amd_smn_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 *value, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff810693d0)
Location: arch/x86/kernel/amd_nb.c:96
Inline: False
Direct callers:
  - arch/x86/kernel/amd_nb.c:amd_smn_write
  - arch/x86/kernel/amd_nb.c:amd_smn_read
```
**Symbols:**

```
ffffffff810693d0-ffffffff810694bf: __amd_smn_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 *value, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/kernel/amd_nb.c:102
Inline: False
Direct callers:
  - arch/x86/kernel/amd_nb.c:amd_smn_write
  - arch/x86/kernel/amd_nb.c:amd_smn_read
```
**Symbols:**

```
ffffffff8106c020-ffffffff8106c0e7: __amd_smn_rw (STB_LOCAL)
ffffffff8106c8aa-ffffffff8106c8e5: __amd_smn_rw.cold.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 *value, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/kernel/amd_nb.c:122
Inline: False
Direct callers:
  - arch/x86/kernel/amd_nb.c:amd_smn_write
  - arch/x86/kernel/amd_nb.c:amd_smn_read
```
**Symbols:**

```
ffffffff81071db0-ffffffff81071e77: __amd_smn_rw (STB_LOCAL)
ffffffff8107273a-ffffffff81072775: __amd_smn_rw.cold.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 *value, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/kernel/amd_nb.c:123
Inline: False
Direct callers:
  - arch/x86/kernel/amd_nb.c:amd_smn_write
  - arch/x86/kernel/amd_nb.c:amd_smn_read
```
**Symbols:**

```
ffffffff810758f0-ffffffff810759b7: __amd_smn_rw (STB_LOCAL)
ffffffff81076245-ffffffff81076280: __amd_smn_rw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 *value, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/kernel/amd_nb.c:129
Inline: False
Direct callers:
  - arch/x86/kernel/amd_nb.c:amd_smn_write
  - arch/x86/kernel/amd_nb.c:amd_smn_read
```
**Symbols:**

```
ffffffff810768c0-ffffffff81076987: __amd_smn_rw (STB_LOCAL)
ffffffff81077215-ffffffff81077250: __amd_smn_rw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 *value, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/kernel/amd_nb.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/amd_nb.c:amd_smn_write
  - arch/x86/kernel/amd_nb.c:amd_smn_read
```
**Symbols:**

```
ffffffff8107db60-ffffffff8107dc29: __amd_smn_rw (STB_LOCAL)
ffffffff8107e545-ffffffff8107e580: __amd_smn_rw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 *value, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/kernel/amd_nb.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/amd_nb.c:amd_smn_write
  - arch/x86/kernel/amd_nb.c:amd_smn_read
```
**Symbols:**

```
ffffffff8107d840-ffffffff8107d909: __amd_smn_rw (STB_LOCAL)
ffffffff81bd7f8e-ffffffff81bd7fc9: __amd_smn_rw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 *value, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/kernel/amd_nb.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/amd_nb.c:amd_smn_write
  - arch/x86/kernel/amd_nb.c:amd_smn_read
```
**Symbols:**

```
ffffffff8107e970-ffffffff8107ea39: __amd_smn_rw (STB_LOCAL)
ffffffff81bc9e40-ffffffff81bc9e7b: __amd_smn_rw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 *value, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/kernel/amd_nb.c:145
Inline: False
Direct callers:
  - arch/x86/kernel/amd_nb.c:amd_smn_write
  - arch/x86/kernel/amd_nb.c:amd_smn_read
```
**Symbols:**

```
ffffffff8108d600-ffffffff8108d6c9: __amd_smn_rw (STB_LOCAL)
ffffffff81c9ef76-ffffffff81c9efb1: __amd_smn_rw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 *value, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/kernel/amd_nb.c:145
Inline: False
Direct callers:
  - arch/x86/kernel/amd_nb.c:amd_smn_write
  - arch/x86/kernel/amd_nb.c:amd_smn_read
```
**Symbols:**

```
ffffffff8109e1a0-ffffffff8109e276: __amd_smn_rw (STB_LOCAL)
ffffffff81e4e3d0-ffffffff81e4e409: __amd_smn_rw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 *value, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff810b5450)
Location: arch/x86/kernel/amd_nb.c:158
Inline: False
Direct callers:
  - arch/x86/kernel/amd_nb.c:amd_smn_write
  - arch/x86/kernel/amd_nb.c:amd_smn_read
```
**Symbols:**

```
ffffffff810b5450-ffffffff810b5547: __amd_smn_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 *value, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff810b8520)
Location: arch/x86/kernel/amd_nb.c:166
Inline: False
Direct callers:
  - arch/x86/kernel/amd_nb.c:amd_smn_write
  - arch/x86/kernel/amd_nb.c:amd_smn_read
```
**Symbols:**

```
ffffffff810b8520-ffffffff810b8617: __amd_smn_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 *value, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff810bf960)
Location: arch/x86/kernel/amd_nb.c:182
Inline: False
Direct callers:
  - arch/x86/kernel/amd_nb.c:amd_smn_write
  - arch/x86/kernel/amd_nb.c:amd_smn_read
```
**Symbols:**

```
ffffffff810bf960-ffffffff810bfa57: __amd_smn_rw (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
int __amd_smn_rw(u16 node, u32 address, u32 *value, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/kernel/amd_nb.c:129
Inline: False
Direct callers:
  - arch/x86/kernel/amd_nb.c:amd_smn_write
  - arch/x86/kernel/amd_nb.c:amd_smn_read
```
**Symbols:**

```
ffffffff810758c0-ffffffff81075987: __amd_smn_rw (STB_LOCAL)
ffffffff81076215-ffffffff81076250: __amd_smn_rw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 *value, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/kernel/amd_nb.c:129
Inline: False
Direct callers:
  - arch/x86/kernel/amd_nb.c:amd_smn_write
  - arch/x86/kernel/amd_nb.c:amd_smn_read
```
**Symbols:**

```
ffffffff810658b0-ffffffff81065977: __amd_smn_rw (STB_LOCAL)
ffffffff810661e5-ffffffff81066220: __amd_smn_rw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 *value, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/kernel/amd_nb.c:129
Inline: False
Direct callers:
  - arch/x86/kernel/amd_nb.c:amd_smn_write
  - arch/x86/kernel/amd_nb.c:amd_smn_read
```
**Symbols:**

```
ffffffff81075870-ffffffff81075937: __amd_smn_rw (STB_LOCAL)
ffffffff810761c5-ffffffff81076200: __amd_smn_rw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 *value, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/kernel/amd_nb.c:129
Inline: False
Direct callers:
  - arch/x86/kernel/amd_nb.c:amd_smn_write
  - arch/x86/kernel/amd_nb.c:amd_smn_read
```
**Symbols:**

```
ffffffff810778d0-ffffffff81077997: __amd_smn_rw (STB_LOCAL)
ffffffff81078225-ffffffff81078260: __amd_smn_rw.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
