# Function: <code>domain_update_dirty_limit</code>

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
void domain_update_dirty_limit(struct dirty_throttle_control *dtc, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812a4d90)
Location: mm/page-writeback.c:1150
Inline: False
Direct callers:
  - mm/page-writeback.c:__wb_update_bandwidth
  - mm/page-writeback.c:__wb_update_bandwidth
```
**Symbols:**

```
ffffffff812a4d90-ffffffff812a4e13: domain_update_dirty_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void domain_update_dirty_limit(struct dirty_throttle_control *dtc, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812fc190)
Location: mm/page-writeback.c:1147
Inline: False
Direct callers:
  - mm/page-writeback.c:__wb_update_bandwidth
  - mm/page-writeback.c:__wb_update_bandwidth
```
**Symbols:**

```
ffffffff812fc190-ffffffff812fc21c: domain_update_dirty_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void domain_update_dirty_limit(struct dirty_throttle_control *dtc, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81366410)
Location: mm/page-writeback.c:1259
Inline: False
Direct callers:
  - mm/page-writeback.c:__wb_update_bandwidth
  - mm/page-writeback.c:__wb_update_bandwidth
```
**Symbols:**

```
ffffffff81366410-ffffffff8136649c: domain_update_dirty_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void domain_update_dirty_limit(struct dirty_throttle_control *dtc, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff813988b0)
Location: mm/page-writeback.c:1259
Inline: False
Direct callers:
  - mm/page-writeback.c:__wb_update_bandwidth
  - mm/page-writeback.c:__wb_update_bandwidth
```
**Symbols:**

```
ffffffff813988b0-ffffffff8139893c: domain_update_dirty_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void domain_update_dirty_limit(struct dirty_throttle_control *dtc, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff813c26b0)
Location: mm/page-writeback.c:1259
Inline: False
Direct callers:
  - mm/page-writeback.c:__wb_update_bandwidth
  - mm/page-writeback.c:__wb_update_bandwidth
```
**Symbols:**

```
ffffffff813c26b0-ffffffff813c273f: domain_update_dirty_limit (STB_LOCAL)
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
