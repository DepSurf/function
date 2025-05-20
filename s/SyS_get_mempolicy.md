# Function: <code>SyS_get_mempolicy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int SyS_get_mempolicy(long int policy, long int nmask, long int maxnode, long int addr, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811e18a0)
Location: mm/mempolicy.c:1435
Inline: True
Inline callers:
  - mm/mempolicy.c:compat_SyS_get_mempolicy
```
**Symbols:**

```
ffffffff811e18a0-ffffffff811e194d: SyS_get_mempolicy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int SyS_get_mempolicy(long int policy, long int nmask, long int maxnode, long int addr, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812003a7)
Location: mm/mempolicy.c:1467
Inline: True
Inline callers:
  - mm/mempolicy.c:compat_SyS_get_mempolicy
```
**Symbols:**

```
ffffffff81200280-ffffffff8120032d: SyS_get_mempolicy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int SyS_get_mempolicy(long int policy, long int nmask, long int maxnode, long int addr, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812116e8)
Location: mm/mempolicy.c:1469
Inline: True
Inline callers:
  - mm/mempolicy.c:C_SYSC_get_mempolicy
```
**Symbols:**

```
ffffffff81211f10-ffffffff81211f20: SyS_get_mempolicy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int SyS_get_mempolicy(long int policy, long int nmask, long int maxnode, long int addr, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8121d017)
Location: mm/mempolicy.c:1398
Inline: True
Inline callers:
  - mm/mempolicy.c:C_SYSC_get_mempolicy
```
**Symbols:**

```
ffffffff8121d2d0-ffffffff8121d2e0: SyS_get_mempolicy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int SyS_get_mempolicy(long int policy, long int nmask, long int maxnode, long int addr, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81238207)
Location: mm/mempolicy.c:1455
Inline: True
Inline callers:
  - mm/mempolicy.c:C_SYSC_get_mempolicy
```
**Symbols:**

```
ffffffff812384c0-ffffffff812384d0: SyS_get_mempolicy (STB_GLOBAL)
```
</details>
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
In <code>5.13</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
