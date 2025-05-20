# Function: <code>md_in_flight</code>

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
In drivers/md/dm.c (ffffffff816a123d)
Location: drivers/md/dm.c:667
Inline: True
Inline callers:
  - drivers/md/dm.c:rq_completed
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_request_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int md_in_flight(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81702575)
Location: drivers/md/dm.c:499
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
Direct callers:
  - drivers/md/dm-rq.c:dm_old_request_fn
  - drivers/md/dm-rq.c:rq_completed
```
**Symbols:**

```
ffffffff81703950-ffffffff81703969: md_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int md_in_flight(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81734477)
Location: drivers/md/dm.c:499
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
Direct callers:
  - drivers/md/dm-rq.c:dm_old_request_fn
  - drivers/md/dm-rq.c:rq_completed
```
**Symbols:**

```
ffffffff81735810-ffffffff81735829: md_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int md_in_flight(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174d858)
Location: drivers/md/dm.c:497
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
Direct callers:
  - drivers/md/dm-rq.c:dm_old_request_fn
  - drivers/md/dm-rq.c:rq_completed
```
**Symbols:**

```
ffffffff8174ec10-ffffffff8174ec29: md_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int md_in_flight(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817bf948)
Location: drivers/md/dm.c:504
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
Direct callers:
  - drivers/md/dm-rq.c:dm_old_request_fn
  - drivers/md/dm-rq.c:rq_completed
```
**Symbols:**

```
ffffffff817c0e50-ffffffff817c0e69: md_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int md_in_flight(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818079c1)
Location: drivers/md/dm.c:598
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
Direct callers:
  - drivers/md/dm-rq.c:dm_old_request_fn
  - drivers/md/dm-rq.c:rq_completed
```
**Symbols:**

```
ffffffff81809570-ffffffff81809589: md_in_flight (STB_GLOBAL)
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
In drivers/md/dm.c (ffffffff81833e31)
Location: drivers/md/dm.c:663
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
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
In drivers/md/dm.c (ffffffff81875c6f)
Location: drivers/md/dm.c:643
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
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
In drivers/md/dm.c (ffffffff818a7a6f)
Location: drivers/md/dm.c:643
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010afc850)
Location: drivers/md/dm.c:643
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdd228)
Location: drivers/md/dm.c:643
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bebbcc)
Location: drivers/md/dm.c:643
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006edc0e)
Location: drivers/md/dm.c:643
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
```
</details>
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
In drivers/md/dm.c (ffffffff8184d8ef)
Location: drivers/md/dm.c:643
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81814f0f)
Location: drivers/md/dm.c:643
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189cf1f)
Location: drivers/md/dm.c:643
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
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
In drivers/md/dm.c (ffffffff818b927f)
Location: drivers/md/dm.c:643
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
