# Function: <code>__se_compat_sys_get_mempolicy</code>

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
In mm/mempolicy.c (ffffffff8125b825)
Location: mm/mempolicy.c:1506
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_get_mempolicy
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
In mm/mempolicy.c (ffffffff812700d5)
Location: mm/mempolicy.c:1546
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_get_mempolicy
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
In mm/mempolicy.c (ffffffff8128b6e5)
Location: mm/mempolicy.c:1592
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_get_mempolicy
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
In mm/mempolicy.c (ffffffff8129b255)
Location: mm/mempolicy.c:1594
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_get_mempolicy
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
In mm/mempolicy.c (ffffffff812ce525)
Location: mm/mempolicy.c:1663
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_get_mempolicy
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
In mm/mempolicy.c (ffffffff812d94b5)
Location: mm/mempolicy.c:1639
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_get_mempolicy
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
In mm/mempolicy.c (ffffffff812e0d35)
Location: mm/mempolicy.c:1653
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_get_mempolicy
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
In mm/mempolicy.c (ffff800010339cf0)
Location: mm/mempolicy.c:1594
Inline: True
Inline callers:
  - mm/mempolicy.c:__arm64_compat_sys_get_mempolicy
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
long int __se_compat_sys_get_mempolicy(long int policy, long int nmask, long int maxnode, long int addr, long int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c0000000004144c0)
Location: mm/mempolicy.c:1594
Inline: False
```
**Symbols:**

```
c0000000004144c0-c0000000004146e4: __se_compat_sys_get_mempolicy (STB_GLOBAL)
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
In mm/mempolicy.c (ffffffff81293835)
Location: mm/mempolicy.c:1594
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_get_mempolicy
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
In mm/mempolicy.c (ffffffff81285445)
Location: mm/mempolicy.c:1594
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_get_mempolicy
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
In mm/mempolicy.c (ffffffff81291645)
Location: mm/mempolicy.c:1594
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_get_mempolicy
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
In mm/mempolicy.c (ffffffff812a1455)
Location: mm/mempolicy.c:1594
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_get_mempolicy
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
