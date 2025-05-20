# Function: <code>__se_compat_sys_set_mempolicy</code>

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
In mm/mempolicy.c (ffffffff8125ae75)
Location: mm/mempolicy.c:1536
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_set_mempolicy
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
In mm/mempolicy.c (ffffffff8126f635)
Location: mm/mempolicy.c:1576
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_set_mempolicy
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
In mm/mempolicy.c (ffffffff8128ac15)
Location: mm/mempolicy.c:1622
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_set_mempolicy
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
In mm/mempolicy.c (ffffffff8129a785)
Location: mm/mempolicy.c:1624
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_set_mempolicy
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
In mm/mempolicy.c (ffffffff812cdd25)
Location: mm/mempolicy.c:1693
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_set_mempolicy
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
In mm/mempolicy.c (ffffffff812d8c65)
Location: mm/mempolicy.c:1669
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_set_mempolicy
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
In mm/mempolicy.c (ffffffff812e0335)
Location: mm/mempolicy.c:1683
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_set_mempolicy
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
In mm/mempolicy.c (ffff800010339120)
Location: mm/mempolicy.c:1624
Inline: True
Inline callers:
  - mm/mempolicy.c:__arm64_compat_sys_set_mempolicy
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
long int __se_compat_sys_set_mempolicy(long int mode, long int nmask, long int maxnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000413a30)
Location: mm/mempolicy.c:1624
Inline: False
```
**Symbols:**

```
c000000000413a30-c000000000413b64: __se_compat_sys_set_mempolicy (STB_GLOBAL)
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
In mm/mempolicy.c (ffffffff81292d65)
Location: mm/mempolicy.c:1624
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_set_mempolicy
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
In mm/mempolicy.c (ffffffff81284975)
Location: mm/mempolicy.c:1624
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_set_mempolicy
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
In mm/mempolicy.c (ffffffff81290b75)
Location: mm/mempolicy.c:1624
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_set_mempolicy
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
In mm/mempolicy.c (ffffffff812a09a5)
Location: mm/mempolicy.c:1624
Inline: True
Inline callers:
  - mm/mempolicy.c:__x32_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_compat_sys_set_mempolicy
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
