# Function: <code>dd_owned_by_driver</code>

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
u32 dd_owned_by_driver(struct deadline_data *dd, enum dd_prio prio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81600530)
Location: block/mq-deadline.c:968
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_owned_by_driver_show
  - block/mq-deadline.c:dd_owned_by_driver_show
  - block/mq-deadline.c:dd_owned_by_driver_show
```
**Symbols:**

```
ffffffff81600530-ffffffff816006db: dd_owned_by_driver (STB_LOCAL)
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
In block/mq-deadline.c (ffffffff816b2b4c)
Location: block/mq-deadline.c:1028
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_owned_by_driver_show
  - block/mq-deadline.c:dd_owned_by_driver_show
  - block/mq-deadline.c:dd_owned_by_driver_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff817720fc)
Location: block/mq-deadline.c:1099
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_owned_by_driver_show
  - block/mq-deadline.c:dd_owned_by_driver_show
  - block/mq-deadline.c:dd_owned_by_driver_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff817b13cc)
Location: block/mq-deadline.c:1142
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_owned_by_driver_show
  - block/mq-deadline.c:dd_owned_by_driver_show
  - block/mq-deadline.c:dd_owned_by_driver_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff817f51dc)
Location: block/mq-deadline.c:1142
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_owned_by_driver_show
  - block/mq-deadline.c:dd_owned_by_driver_show
  - block/mq-deadline.c:dd_owned_by_driver_show
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
</ul>
