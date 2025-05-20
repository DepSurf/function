# Function: <code>__wake_up_locked_sync_key</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __wake_up_locked_sync_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810febd0)
Location: kernel/sched/wait.c:210
Inline: False
```
**Symbols:**

```
ffffffff810febd0-ffffffff810febf0: __wake_up_locked_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __wake_up_locked_sync_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fd550)
Location: kernel/sched/wait.c:225
Inline: False
```
**Symbols:**

```
ffffffff810fd550-ffffffff810fd570: __wake_up_locked_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __wake_up_locked_sync_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ff910)
Location: kernel/sched/wait.c:225
Inline: False
```
**Symbols:**

```
ffffffff810ff910-ffffffff810ff930: __wake_up_locked_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __wake_up_locked_sync_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff8111ba00)
Location: kernel/sched/wait.c:225
Inline: False
```
**Symbols:**

```
ffffffff8111ba00-ffffffff8111ba20: __wake_up_locked_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __wake_up_locked_sync_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113bd80)
Location: kernel/sched/wait.c:224
Inline: False
```
**Symbols:**

```
ffffffff8113bd80-ffffffff8113bdb4: __wake_up_locked_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __wake_up_locked_sync_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81166870)
Location: kernel/sched/wait.c:228
Inline: False
```
**Symbols:**

```
ffffffff81166870-ffffffff811668a4: __wake_up_locked_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __wake_up_locked_sync_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81176ce0)
Location: kernel/sched/wait.c:228
Inline: False
```
**Symbols:**

```
ffffffff81176ce0-ffffffff81176d14: __wake_up_locked_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __wake_up_locked_sync_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81184cb0)
Location: kernel/sched/wait.c:193
Inline: False
```
**Symbols:**

```
ffffffff81184cb0-ffffffff81184cde: __wake_up_locked_sync_key (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
