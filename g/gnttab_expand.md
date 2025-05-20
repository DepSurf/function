# Function: <code>gnttab_expand</code>

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
In drivers/xen/grant-table.c (ffffffff814c4f5a)
Location: drivers/xen/grant-table.c:1067
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
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
In drivers/xen/grant-table.c (ffffffff815156e0)
Location: drivers/xen/grant-table.c:1066
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81541b70)
Location: drivers/xen/grant-table.c:1066
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8155594a)
Location: drivers/xen/grant-table.c:1067
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815b95b0)
Location: drivers/xen/grant-table.c:1259
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815f2f36)
Location: drivers/xen/grant-table.c:1259
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
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
In drivers/xen/grant-table.c (ffffffff8160d506)
Location: drivers/xen/grant-table.c:1387
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
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
In drivers/xen/grant-table.c (ffffffff81640f40)
Location: drivers/xen/grant-table.c:1387
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
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
In drivers/xen/grant-table.c (ffffffff81663900)
Location: drivers/xen/grant-table.c:1386
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gnttab_expand(unsigned int req_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81712be0)
Location: drivers/xen/grant-table.c:1383
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:get_free_entries
```
**Symbols:**

```
ffffffff81712be0-ffffffff81712c8f: gnttab_expand (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gnttab_expand(unsigned int req_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8172f9e0)
Location: drivers/xen/grant-table.c:1506
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:get_free_entries
```
**Symbols:**

```
ffffffff8172f9e0-ffffffff8172fa8f: gnttab_expand (STB_LOCAL)
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
In drivers/xen/grant-table.c (ffffffff8171342b)
Location: drivers/xen/grant-table.c:1506
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8179007b)
Location: drivers/xen/grant-table.c:1513
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int gnttab_expand(unsigned int req_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff818c82b0)
Location: drivers/xen/grant-table.c:1577
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:get_free_entries_seq
  - drivers/xen/grant-table.c:get_free_entries_seq
  - drivers/xen/grant-table.c:get_free_entries
```
**Symbols:**

```
ffffffff818c82b0-ffffffff818c84b9: gnttab_expand (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gnttab_expand(unsigned int req_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a18ca0)
Location: drivers/xen/grant-table.c:1580
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:get_free_entries_seq
  - drivers/xen/grant-table.c:get_free_entries_seq
  - drivers/xen/grant-table.c:get_free_entries
```
**Symbols:**

```
ffffffff81a18ca0-ffffffff81a18ea9: gnttab_expand (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gnttab_expand(unsigned int req_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a61d20)
Location: drivers/xen/grant-table.c:1598
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:get_free_entries_seq
  - drivers/xen/grant-table.c:get_free_entries_seq
  - drivers/xen/grant-table.c:get_free_entries
```
**Symbols:**

```
ffffffff81a61d20-ffffffff81a61f29: gnttab_expand (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gnttab_expand(unsigned int req_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81ab4550)
Location: drivers/xen/grant-table.c:1596
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:get_free_entries_seq
  - drivers/xen/grant-table.c:get_free_entries_seq
  - drivers/xen/grant-table.c:get_free_entries
```
**Symbols:**

```
ffffffff81ab4550-ffffffff81ab4759: gnttab_expand (STB_LOCAL)
```
</details>
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
In drivers/xen/grant-table.c (ffff80001082dca4)
Location: drivers/xen/grant-table.c:1386
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81629770)
Location: drivers/xen/grant-table.c:1386
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81657740)
Location: drivers/xen/grant-table.c:1386
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
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
In drivers/xen/grant-table.c (ffffffff81671d40)
Location: drivers/xen/grant-table.c:1386
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
