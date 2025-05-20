# Function: <code>gnttab_set_free</code>

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
void gnttab_set_free(unsigned int start, unsigned int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff818c7360)
Location: drivers/xen/grant-table.c:356
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_expand
```
**Symbols:**

```
ffffffff818c7360-ffffffff818c742f: gnttab_set_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gnttab_set_free(unsigned int start, unsigned int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a17e90)
Location: drivers/xen/grant-table.c:356
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_expand
```
**Symbols:**

```
ffffffff81a17e90-ffffffff81a17f5f: gnttab_set_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gnttab_set_free(unsigned int start, unsigned int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a60f20)
Location: drivers/xen/grant-table.c:356
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_expand
```
**Symbols:**

```
ffffffff81a60f20-ffffffff81a60fef: gnttab_set_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gnttab_set_free(unsigned int start, unsigned int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81ab3750)
Location: drivers/xen/grant-table.c:356
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_expand
```
**Symbols:**

```
ffffffff81ab3750-ffffffff81ab381f: gnttab_set_free (STB_LOCAL)
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
