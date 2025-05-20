# Function: <code>arch_xen_unpopulated_init</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int arch_xen_unpopulated_init(struct resource **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/unpopulated-alloc.c (ffffffff834b1cac)
Location: drivers/xen/unpopulated-alloc.c:27
Inline: False
Direct callers:
  - drivers/xen/unpopulated-alloc.c:unpopulated_init
```
**Symbols:**

```
ffffffff834b1cac-ffffffff834b1cc6: arch_xen_unpopulated_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int arch_xen_unpopulated_init(struct resource **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/unpopulated-alloc.c (ffffffff83eec050)
Location: drivers/xen/unpopulated-alloc.c:27
Inline: False
Direct callers:
  - drivers/xen/unpopulated-alloc.c:unpopulated_init
```
**Symbols:**

```
ffffffff83eec050-ffffffff83eec06a: arch_xen_unpopulated_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int arch_xen_unpopulated_init(struct resource **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/unpopulated-alloc.c (ffffffff83711d40)
Location: drivers/xen/unpopulated-alloc.c:27
Inline: False
Direct callers:
  - drivers/xen/unpopulated-alloc.c:unpopulated_init
```
**Symbols:**

```
ffffffff83711d40-ffffffff83711d5a: arch_xen_unpopulated_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int arch_xen_unpopulated_init(struct resource **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/unpopulated-alloc.c (ffffffff839456d0)
Location: drivers/xen/unpopulated-alloc.c:27
Inline: False
Direct callers:
  - drivers/xen/unpopulated-alloc.c:unpopulated_init
```
**Symbols:**

```
ffffffff839456d0-ffffffff839456ea: arch_xen_unpopulated_init (STB_WEAK)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
