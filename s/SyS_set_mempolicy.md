# Function: <code>SyS_set_mempolicy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int SyS_set_mempolicy(long int mode, long int nmask, long int maxnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811e1640)
Location: mm/mempolicy.c:1320
Inline: True
Inline callers:
  - mm/mempolicy.c:compat_SyS_set_mempolicy
```
**Symbols:**

```
ffffffff811e1640-ffffffff811e16cc: SyS_set_mempolicy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int SyS_set_mempolicy(long int mode, long int nmask, long int maxnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8120055f)
Location: mm/mempolicy.c:1352
Inline: True
Inline callers:
  - mm/mempolicy.c:compat_SyS_set_mempolicy
```
**Symbols:**

```
ffffffff81200020-ffffffff812000ac: SyS_set_mempolicy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int SyS_set_mempolicy(long int mode, long int nmask, long int maxnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81210e36)
Location: mm/mempolicy.c:1354
Inline: True
Inline callers:
  - mm/mempolicy.c:C_SYSC_set_mempolicy
```
**Symbols:**

```
ffffffff81211ef0-ffffffff81211f00: SyS_set_mempolicy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int SyS_set_mempolicy(long int mode, long int nmask, long int maxnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8121c7b0)
Location: mm/mempolicy.c:1283
Inline: True
Inline callers:
  - mm/mempolicy.c:C_SYSC_set_mempolicy
```
**Symbols:**

```
ffffffff8121d2b0-ffffffff8121d2c0: SyS_set_mempolicy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int SyS_set_mempolicy(long int mode, long int nmask, long int maxnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81237960)
Location: mm/mempolicy.c:1346
Inline: True
Inline callers:
  - mm/mempolicy.c:C_SYSC_set_mempolicy
```
**Symbols:**

```
ffffffff812384a0-ffffffff812384b0: SyS_set_mempolicy (STB_GLOBAL)
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
