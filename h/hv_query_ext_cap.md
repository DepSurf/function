# Function: <code>hv_query_ext_cap</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool hv_query_ext_cap(u64 cap_query);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81031258)
Location: arch/x86/hyperv/hv_init.c:627
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff81bc5263-ffffffff81bc5283: hv_query_ext_cap.cold (STB_LOCAL)
ffffffff81031220-ffffffff810312c7: hv_query_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool hv_query_ext_cap(u64 cap_query);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/hv/hv_common.c (ffffffff81a60fe6)
Location: drivers/hv/hv_common.c:174
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff81d32e8e-ffffffff81d32ec2: hv_query_ext_cap.cold (STB_LOCAL)
ffffffff81a60fa0-ffffffff81a6103d: hv_query_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool hv_query_ext_cap(u64 cap_query);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hv/hv_common.c (0)
Location: drivers/hv/hv_common.c:177
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff81eff2e7-ffffffff81eff303: hv_query_ext_cap.cold (STB_LOCAL)
ffffffff81bd15c0-ffffffff81bd16b6: hv_query_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool hv_query_ext_cap(u64 cap_query);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hv/hv_common.c (0)
Location: drivers/hv/hv_common.c:177
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff820aa3e5-ffffffff820aa3fa: hv_query_ext_cap.cold (STB_LOCAL)
ffffffff81d7d040-ffffffff81d7d127: hv_query_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool hv_query_ext_cap(u64 cap_query);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hv/hv_common.c (0)
Location: drivers/hv/hv_common.c:411
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff8212b8e4-ffffffff8212b8f9: hv_query_ext_cap.cold (STB_LOCAL)
ffffffff81deb430-ffffffff81deb517: hv_query_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool hv_query_ext_cap(u64 cap_query);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hv/hv_common.c (0)
Location: drivers/hv/hv_common.c:440
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff8220d535-ffffffff8220d54a: hv_query_ext_cap.cold (STB_LOCAL)
ffffffff81ea18b0-ffffffff81ea1926: hv_query_ext_cap (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
