# Function: <code>gnttab_read_frame_v1</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int gnttab_read_frame_v1(grant_ref_t ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8178edc0)
Location: drivers/xen/grant-table.c:337
Inline: False
```
**Symbols:**

```
ffffffff8178edc0-ffffffff8178edd8: gnttab_read_frame_v1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int gnttab_read_frame_v1(grant_ref_t ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff818c6e30)
Location: drivers/xen/grant-table.c:481
Inline: False
```
**Symbols:**

```
ffffffff818c6e30-ffffffff818c6e4e: gnttab_read_frame_v1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int gnttab_read_frame_v1(grant_ref_t ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a17860)
Location: drivers/xen/grant-table.c:481
Inline: False
```
**Symbols:**

```
ffffffff81a17860-ffffffff81a1787e: gnttab_read_frame_v1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int gnttab_read_frame_v1(grant_ref_t ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a608f0)
Location: drivers/xen/grant-table.c:481
Inline: False
```
**Symbols:**

```
ffffffff81a608f0-ffffffff81a6090e: gnttab_read_frame_v1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int gnttab_read_frame_v1(grant_ref_t ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81ab30c0)
Location: drivers/xen/grant-table.c:479
Inline: False
```
**Symbols:**

```
ffffffff81ab30c0-ffffffff81ab30de: gnttab_read_frame_v1 (STB_LOCAL)
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
