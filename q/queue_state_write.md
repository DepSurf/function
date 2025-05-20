# Function: <code>queue_state_write</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t queue_state_write(void *data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81459b60)
Location: block/blk-mq-debugfs.c:93
Inline: False
```
**Symbols:**

```
ffffffff81459b60-ffffffff81459cc3: queue_state_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t queue_state_write(void *data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81485830)
Location: block/blk-mq-debugfs.c:91
Inline: False
```
**Symbols:**

```
ffffffff81485830-ffffffff81485993: queue_state_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
ssize_t queue_state_write(void *data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (0)
Location: block/blk-mq-debugfs.c:149
Inline: False
```
**Symbols:**

```
ffffffff814ba6f0-ffffffff814ba824: queue_state_write (STB_LOCAL)
ffffffff814bb337-ffffffff814bb381: queue_state_write.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
ssize_t queue_state_write(void *data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (0)
Location: block/blk-mq-debugfs.c:155
Inline: False
```
**Symbols:**

```
ffffffff814ce880-ffffffff814ce9b1: queue_state_write (STB_LOCAL)
ffffffff814cf677-ffffffff814cf6c1: queue_state_write.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t queue_state_write(void *data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (0)
Location: block/blk-mq-debugfs.c:141
Inline: False
```
**Symbols:**

```
ffffffff814fd160-ffffffff814fd28f: queue_state_write (STB_LOCAL)
ffffffff814fdd97-ffffffff814fdde1: queue_state_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t queue_state_write(void *data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (0)
Location: block/blk-mq-debugfs.c:141
Inline: False
```
**Symbols:**

```
ffffffff8151b0b0-ffffffff8151b1df: queue_state_write (STB_LOCAL)
ffffffff8151bcd7-ffffffff8151bd21: queue_state_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t queue_state_write(void *data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (0)
Location: block/blk-mq-debugfs.c:144
Inline: False
```
**Symbols:**

```
ffffffff8157b360-ffffffff8157b48f: queue_state_write (STB_LOCAL)
ffffffff8157c48a-ffffffff8157c4d4: queue_state_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t queue_state_write(void *data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (0)
Location: block/blk-mq-debugfs.c:146
Inline: False
```
**Symbols:**

```
ffffffff81598420-ffffffff8159854f: queue_state_write (STB_LOCAL)
ffffffff81bf3ec3-ffffffff81bf3f0d: queue_state_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t queue_state_write(void *data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (0)
Location: block/blk-mq-debugfs.c:146
Inline: False
```
**Symbols:**

```
ffffffff8159f240-ffffffff8159f35a: queue_state_write (STB_LOCAL)
ffffffff81be5d1d-ffffffff81be5d67: queue_state_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t queue_state_write(void *data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (0)
Location: block/blk-mq-debugfs.c:147
Inline: False
```
**Symbols:**

```
ffffffff816079f0-ffffffff81607b0a: queue_state_write (STB_LOCAL)
ffffffff81cda507-ffffffff81cda551: queue_state_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t queue_state_write(void *data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (0)
Location: block/blk-mq-debugfs.c:147
Inline: False
```
**Symbols:**

```
ffffffff816bb300-ffffffff816bb424: queue_state_write (STB_LOCAL)
ffffffff81e8e0af-ffffffff81e8e0f9: queue_state_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t queue_state_write(void *data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8177ba60)
Location: block/blk-mq-debugfs.c:146
Inline: False
```
**Symbols:**

```
ffffffff8177ba60-ffffffff8177bbcd: queue_state_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t queue_state_write(void *data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff817bb570)
Location: block/blk-mq-debugfs.c:122
Inline: False
```
**Symbols:**

```
ffffffff817bb570-ffffffff817bb6e0: queue_state_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t queue_state_write(void *data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff817ffc30)
Location: block/blk-mq-debugfs.c:122
Inline: False
```
**Symbols:**

```
ffffffff817ffc30-ffffffff817ffd9d: queue_state_write (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
ssize_t queue_state_write(void *data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffff800010623b30)
Location: block/blk-mq-debugfs.c:141
Inline: False
```
**Symbols:**

```
ffff800010623b30-ffff800010623dbc: queue_state_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t queue_state_write(void *data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (c07cacb8)
Location: block/blk-mq-debugfs.c:141
Inline: False
```
**Symbols:**

```
c07cacb8-c07cae7c: queue_state_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t queue_state_write(void *data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (c0000000007c3690)
Location: block/blk-mq-debugfs.c:141
Inline: False
```
**Symbols:**

```
c0000000007c3690-c0000000007c3c08: queue_state_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t queue_state_write(void *data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffe0004550dc)
Location: block/blk-mq-debugfs.c:141
Inline: False
```
**Symbols:**

```
ffffffe0004550dc-ffffffe00045520c: queue_state_write (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t queue_state_write(void *data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (0)
Location: block/blk-mq-debugfs.c:141
Inline: False
```
**Symbols:**

```
ffffffff81513690-ffffffff815137bf: queue_state_write (STB_LOCAL)
ffffffff815142b7-ffffffff81514301: queue_state_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t queue_state_write(void *data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (0)
Location: block/blk-mq-debugfs.c:141
Inline: False
```
**Symbols:**

```
ffffffff815039a0-ffffffff81503acf: queue_state_write (STB_LOCAL)
ffffffff815045c7-ffffffff81504611: queue_state_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t queue_state_write(void *data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (0)
Location: block/blk-mq-debugfs.c:141
Inline: False
```
**Symbols:**

```
ffffffff8150f720-ffffffff8150f84f: queue_state_write (STB_LOCAL)
ffffffff81510347-ffffffff81510391: queue_state_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t queue_state_write(void *data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (0)
Location: block/blk-mq-debugfs.c:141
Inline: False
```
**Symbols:**

```
ffffffff81528f40-ffffffff8152906f: queue_state_write (STB_LOCAL)
ffffffff81529b07-ffffffff81529b51: queue_state_write.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
