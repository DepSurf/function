# Function: <code>loop_process_work</code>

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
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void loop_process_work(struct loop_worker *worker, struct list_head *cmd_list, struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:2276
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_rootcg_workfn
  - drivers/block/loop.c:loop_workfn
```
**Symbols:**

```
ffffffff8186ff40-ffffffff8187021a: loop_process_work (STB_LOCAL)
ffffffff81d059fc-ffffffff81d05a38: loop_process_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void loop_process_work(struct loop_worker *worker, struct list_head *cmd_list, struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1885
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_rootcg_workfn
  - drivers/block/loop.c:loop_workfn
```
**Symbols:**

```
ffffffff819b7540-ffffffff819b781e: loop_process_work (STB_LOCAL)
ffffffff81ece2cd-ffffffff81ece302: loop_process_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void loop_process_work(struct loop_worker *worker, struct list_head *cmd_list, struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1894
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_rootcg_workfn
  - drivers/block/loop.c:loop_workfn
```
**Symbols:**

```
ffffffff81b2c840-ffffffff81b2cb1e: loop_process_work (STB_LOCAL)
ffffffff82099b0a-ffffffff82099b3f: loop_process_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void loop_process_work(struct loop_worker *worker, struct list_head *cmd_list, struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1936
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_rootcg_workfn
  - drivers/block/loop.c:loop_workfn
```
**Symbols:**

```
ffffffff81b7cab0-ffffffff81b7cdf2: loop_process_work (STB_LOCAL)
ffffffff8211abb9-ffffffff8211abdd: loop_process_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void loop_process_work(struct loop_worker *worker, struct list_head *cmd_list, struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1930
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_rootcg_workfn
  - drivers/block/loop.c:loop_workfn
```
**Symbols:**

```
ffffffff81bd09f0-ffffffff81bd0d88: loop_process_work (STB_LOCAL)
ffffffff821f8a3f-ffffffff821f8a63: loop_process_work.cold (STB_LOCAL)
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
