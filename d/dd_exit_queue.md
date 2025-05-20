# Function: <code>dd_exit_queue</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void dd_exit_queue(struct elevator_queue *e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff814c8240)
Location: block/mq-deadline.c:402
Inline: True
```
**Symbols:**

```
ffffffff814c8240-ffffffff814c8272: dd_exit_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void dd_exit_queue(struct elevator_queue *e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff814f6af0)
Location: block/mq-deadline.c:403
Inline: True
```
**Symbols:**

```
ffffffff814f6af0-ffffffff814f6b22: dd_exit_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void dd_exit_queue(struct elevator_queue *e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff815149a0)
Location: block/mq-deadline.c:393
Inline: True
```
**Symbols:**

```
ffffffff815149a0-ffffffff815149d2: dd_exit_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void dd_exit_queue(struct elevator_queue *e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff815755b0)
Location: block/mq-deadline.c:393
Inline: True
```
**Symbols:**

```
ffffffff815755b0-ffffffff815755e2: dd_exit_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void dd_exit_queue(struct elevator_queue *e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff815923c0)
Location: block/mq-deadline.c:395
Inline: True
```
**Symbols:**

```
ffffffff815923c0-ffffffff815923f2: dd_exit_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dd_exit_queue(struct elevator_queue *e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff815990a0)
Location: block/mq-deadline.c:395
Inline: True
```
**Symbols:**

```
ffffffff815990a0-ffffffff815990d2: dd_exit_queue (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void dd_exit_queue(struct elevator_queue *e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffff800010619210)
Location: block/mq-deadline.c:393
Inline: True
```
**Symbols:**

```
ffff800010619210-ffff800010619264: dd_exit_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void dd_exit_queue(struct elevator_queue *e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (c07c41a0)
Location: block/mq-deadline.c:393
Inline: True
```
**Symbols:**

```
c07c41a0-c07c41e8: dd_exit_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dd_exit_queue(struct elevator_queue *e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (c0000000007b8c10)
Location: block/mq-deadline.c:393
Inline: False
```
**Symbols:**

```
c0000000007b8c10-c0000000007b8c78: dd_exit_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void dd_exit_queue(struct elevator_queue *e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffe00044f3b0)
Location: block/mq-deadline.c:393
Inline: True
```
**Symbols:**

```
ffffffe00044f3b0-ffffffe00044f3f2: dd_exit_queue (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void dd_exit_queue(struct elevator_queue *e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff8150cf80)
Location: block/mq-deadline.c:393
Inline: True
```
**Symbols:**

```
ffffffff8150cf80-ffffffff8150cfb2: dd_exit_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void dd_exit_queue(struct elevator_queue *e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff814fd3b0)
Location: block/mq-deadline.c:393
Inline: True
```
**Symbols:**

```
ffffffff814fd3b0-ffffffff814fd3e2: dd_exit_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void dd_exit_queue(struct elevator_queue *e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81509010)
Location: block/mq-deadline.c:393
Inline: True
```
**Symbols:**

```
ffffffff81509010-ffffffff81509042: dd_exit_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void dd_exit_queue(struct elevator_queue *e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff815227b0)
Location: block/mq-deadline.c:393
Inline: True
```
**Symbols:**

```
ffffffff815227b0-ffffffff815227e2: dd_exit_queue (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
