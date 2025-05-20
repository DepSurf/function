# Function: <code>deadline_write1_next_rq_show</code>

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
int deadline_write1_next_rq_show(void *data, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81600ba0)
Location: block/mq-deadline.c:918
Inline: False
```
**Symbols:**

```
ffffffff81600ba0-ffffffff81600bcf: deadline_write1_next_rq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int deadline_write1_next_rq_show(void *data, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff816b31c0)
Location: block/mq-deadline.c:978
Inline: False
```
**Symbols:**

```
ffffffff816b31c0-ffffffff816b31ff: deadline_write1_next_rq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int deadline_write1_next_rq_show(void *data, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff817728f0)
Location: block/mq-deadline.c:1049
Inline: False
```
**Symbols:**

```
ffffffff817728f0-ffffffff8177292f: deadline_write1_next_rq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int deadline_write1_next_rq_show(void *data, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/mq-deadline.c (0)
Location: block/mq-deadline.c:1092
Inline: False
```
**Symbols:**

```
ffffffff817b3870-ffffffff817b3987: deadline_write1_next_rq_show (STB_LOCAL)
ffffffff820f6f2b-ffffffff820f6f48: deadline_write1_next_rq_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int deadline_write1_next_rq_show(void *data, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/mq-deadline.c (0)
Location: block/mq-deadline.c:1092
Inline: False
```
**Symbols:**

```
ffffffff817f7b30-ffffffff817f7c65: deadline_write1_next_rq_show (STB_LOCAL)
ffffffff821d460a-ffffffff821d466f: deadline_write1_next_rq_show.cold (STB_LOCAL)
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
