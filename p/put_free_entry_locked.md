# Function: <code>put_free_entry_locked</code>

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
void put_free_entry_locked(grant_ref_t ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff818c7130)
Location: drivers/xen/grant-table.c:331
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_free_grant_reference_seq
  - drivers/xen/grant-table.c:gnttab_free_grant_references
  - drivers/xen/grant-table.c:gnttab_free_grant_reference
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
**Symbols:**

```
ffffffff818c7130-ffffffff818c71ce: put_free_entry_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void put_free_entry_locked(grant_ref_t ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a17cc0)
Location: drivers/xen/grant-table.c:331
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_free_grant_reference_seq
  - drivers/xen/grant-table.c:gnttab_free_grant_references
  - drivers/xen/grant-table.c:gnttab_free_grant_reference
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
**Symbols:**

```
ffffffff81a17cc0-ffffffff81a17d5e: put_free_entry_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void put_free_entry_locked(grant_ref_t ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a60d50)
Location: drivers/xen/grant-table.c:331
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_free_grant_reference_seq
  - drivers/xen/grant-table.c:gnttab_free_grant_references
  - drivers/xen/grant-table.c:gnttab_free_grant_reference
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
**Symbols:**

```
ffffffff81a60d50-ffffffff81a60dee: put_free_entry_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void put_free_entry_locked(grant_ref_t ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81ab3580)
Location: drivers/xen/grant-table.c:331
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_free_grant_reference_seq
  - drivers/xen/grant-table.c:gnttab_free_grant_references
  - drivers/xen/grant-table.c:gnttab_free_grant_reference
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
**Symbols:**

```
ffffffff81ab3580-ffffffff81ab361e: put_free_entry_locked (STB_LOCAL)
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
