# Function: <code>SYSC_set_mempolicy</code>

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
In mm/mempolicy.c (ffffffff811e164c)
Location: mm/mempolicy.c:1320
Inline: True
Inline callers:
  - mm/mempolicy.c:compat_SyS_set_mempolicy
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
In mm/mempolicy.c (ffffffff8120055f)
Location: mm/mempolicy.c:1352
Inline: True
Inline callers:
  - mm/mempolicy.c:compat_SyS_set_mempolicy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int SYSC_set_mempolicy(int mode, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81210ce0)
Location: mm/mempolicy.c:1354
Inline: False
Direct callers:
  - mm/mempolicy.c:C_SYSC_set_mempolicy
```
**Symbols:**

```
ffffffff81210ce0-ffffffff81210d72: SYSC_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int SYSC_set_mempolicy(int mode, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8121c660)
Location: mm/mempolicy.c:1283
Inline: False
Direct callers:
  - mm/mempolicy.c:C_SYSC_set_mempolicy
```
**Symbols:**

```
ffffffff8121c660-ffffffff8121c6f2: SYSC_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int SYSC_set_mempolicy(int mode, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81237810)
Location: mm/mempolicy.c:1346
Inline: False
Direct callers:
  - mm/mempolicy.c:C_SYSC_set_mempolicy
```
**Symbols:**

```
ffffffff81237810-ffffffff812378a2: SYSC_set_mempolicy (STB_LOCAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
