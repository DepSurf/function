# Function: <code>blkcg_fill_root_iostats</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blkcg_fill_root_iostats();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815846e0)
Location: block/blk-cgroup.c:816
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_print_stat
```
**Symbols:**

```
ffffffff815846e0-ffffffff81584815: blkcg_fill_root_iostats (STB_LOCAL)
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
In block/blk-cgroup.c (ffffffff8158c2cd)
Location: block/blk-cgroup.c:820
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
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
In block/blk-cgroup.c (ffffffff815f18e6)
Location: block/blk-cgroup.c:846
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff816a25c1)
Location: block/blk-cgroup.c:907
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blkcg_fill_root_iostats();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81760fc0)
Location: block/blk-cgroup.c:920
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_print_stat
```
**Symbols:**

```
ffffffff81760fc0-ffffffff81761189: blkcg_fill_root_iostats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blkcg_fill_root_iostats();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817a0180)
Location: block/blk-cgroup.c:1053
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_print_stat
```
**Symbols:**

```
ffffffff817a0180-ffffffff817a0355: blkcg_fill_root_iostats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blkcg_fill_root_iostats();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817e3cb0)
Location: block/blk-cgroup.c:1066
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_print_stat
```
**Symbols:**

```
ffffffff817e3cb0-ffffffff817e3e85: blkcg_fill_root_iostats (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
