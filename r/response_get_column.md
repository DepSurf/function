# Function: <code>response_get_column</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int response_get_column(const struct parsed_resp *resp, int *iter, u8 column, u64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff817bd150)
Location: block/sed-opal.c:1452
Inline: False
Direct callers:
  - block/sed-opal.c:locking_range_status
  - block/sed-opal.c:locking_range_status
  - block/sed-opal.c:locking_range_status
  - block/sed-opal.c:locking_range_status
  - block/sed-opal.c:locking_range_status
  - block/sed-opal.c:locking_range_status
```
**Symbols:**

```
ffffffff817bd150-ffffffff817bd280: response_get_column (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int response_get_column(const struct parsed_resp *resp, int *iter, u8 column, u64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81801810)
Location: block/sed-opal.c:1569
Inline: False
Direct callers:
  - block/sed-opal.c:locking_range_status
  - block/sed-opal.c:locking_range_status
  - block/sed-opal.c:locking_range_status
  - block/sed-opal.c:locking_range_status
  - block/sed-opal.c:locking_range_status
  - block/sed-opal.c:locking_range_status
```
**Symbols:**

```
ffffffff81801810-ffffffff81801940: response_get_column (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
