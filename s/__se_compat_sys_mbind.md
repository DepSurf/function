# Function: <code>__se_compat_sys_mbind</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8125cb95)
Location: mm/mempolicy.c:1557
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_mbind
  - mm/mempolicy.c:__ia32_compat_sys_mbind
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
In mm/mempolicy.c (ffffffff81271475)
Location: mm/mempolicy.c:1597
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_mbind
  - mm/mempolicy.c:__ia32_compat_sys_mbind
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
In mm/mempolicy.c (ffffffff8128ca85)
Location: mm/mempolicy.c:1643
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_mbind
  - mm/mempolicy.c:__ia32_compat_sys_mbind
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
In mm/mempolicy.c (ffffffff8129c6b5)
Location: mm/mempolicy.c:1645
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_mbind
  - mm/mempolicy.c:__ia32_compat_sys_mbind
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d0305)
Location: mm/mempolicy.c:1714
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_mbind
  - mm/mempolicy.c:__ia32_compat_sys_mbind
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812dbe25)
Location: mm/mempolicy.c:1690
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_mbind
  - mm/mempolicy.c:__ia32_compat_sys_mbind
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e3695)
Location: mm/mempolicy.c:1704
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_mbind
  - mm/mempolicy.c:__ia32_compat_sys_mbind
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In mm/mempolicy.c (ffff80001033b3e0)
Location: mm/mempolicy.c:1645
Inline: True
Inline callers:
  - mm/mempolicy.c:__arm64_compat_sys_mbind
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
long int __se_compat_sys_mbind(long int start, long int len, long int mode, long int nmask, long int maxnode, long int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c0000000004161c0)
Location: mm/mempolicy.c:1645
Inline: False
```
**Symbols:**

```
c0000000004161c0-c000000000416324: __se_compat_sys_mbind (STB_GLOBAL)
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
In mm/mempolicy.c (ffffffff81294c95)
Location: mm/mempolicy.c:1645
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_mbind
  - mm/mempolicy.c:__ia32_compat_sys_mbind
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
In mm/mempolicy.c (ffffffff812868a5)
Location: mm/mempolicy.c:1645
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_mbind
  - mm/mempolicy.c:__ia32_compat_sys_mbind
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
In mm/mempolicy.c (ffffffff81292aa5)
Location: mm/mempolicy.c:1645
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_mbind
  - mm/mempolicy.c:__ia32_compat_sys_mbind
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
In mm/mempolicy.c (ffffffff812a2875)
Location: mm/mempolicy.c:1645
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_mbind
  - mm/mempolicy.c:__ia32_compat_sys_mbind
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
