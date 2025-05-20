# Function: <code>SyS_mbind</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int SyS_mbind(long int start, long int len, long int mode, long int nmask, long int maxnode, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811e2a8f)
Location: mm/mempolicy.c:1298
Inline: True
Inline callers:
  - mm/mempolicy.c:compat_SyS_mbind
```
**Symbols:**

```
ffffffff811e2b20-ffffffff811e2bc9: SyS_mbind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int SyS_mbind(long int start, long int len, long int mode, long int nmask, long int maxnode, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81201479)
Location: mm/mempolicy.c:1330
Inline: True
Inline callers:
  - mm/mempolicy.c:compat_SyS_mbind
```
**Symbols:**

```
ffffffff81201500-ffffffff812015a9: SyS_mbind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int SyS_mbind(long int start, long int len, long int mode, long int nmask, long int maxnode, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81213019)
Location: mm/mempolicy.c:1332
Inline: True
Inline callers:
  - mm/mempolicy.c:C_SYSC_mbind
```
**Symbols:**

```
ffffffff81212f20-ffffffff81212f30: SyS_mbind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int SyS_mbind(long int start, long int len, long int mode, long int nmask, long int maxnode, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8121e357)
Location: mm/mempolicy.c:1261
Inline: True
Inline callers:
  - mm/mempolicy.c:C_SYSC_mbind
```
**Symbols:**

```
ffffffff8121e270-ffffffff8121e280: SyS_mbind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int SyS_mbind(long int start, long int len, long int mode, long int nmask, long int maxnode, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812395a7)
Location: mm/mempolicy.c:1324
Inline: True
Inline callers:
  - mm/mempolicy.c:C_SYSC_mbind
```
**Symbols:**

```
ffffffff812394c0-ffffffff812394d0: SyS_mbind (STB_GLOBAL)
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
