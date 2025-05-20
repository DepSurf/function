# Function: <code>ioc_timer_fn</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ioc_timer_fn(struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815127f0)
Location: block/blk-iocost.c:1341
Inline: False
```
**Symbols:**

```
ffffffff815127f0-ffffffff815135d2: ioc_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ioc_timer_fn(struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81573d30)
Location: block/blk-iocost.c:1340
Inline: False
```
**Symbols:**

```
ffffffff81573d30-ffffffff8157494b: ioc_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ioc_timer_fn(struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81590b30)
Location: block/blk-iocost.c:2202
Inline: False
```
**Symbols:**

```
ffffffff81590b30-ffffffff815916d3: ioc_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ioc_timer_fn(struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81597890)
Location: block/blk-iocost.c:2209
Inline: False
```
**Symbols:**

```
ffffffff81597890-ffffffff8159852f: ioc_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ioc_timer_fn(struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2209
Inline: False
```
**Symbols:**

```
ffffffff815fefa0-ffffffff815ffcc4: ioc_timer_fn (STB_LOCAL)
ffffffff81cd9f27-ffffffff81cd9f3c: ioc_timer_fn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ioc_timer_fn(struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2202
Inline: False
```
**Symbols:**

```
ffffffff816b0ee0-ffffffff816b1d57: ioc_timer_fn (STB_LOCAL)
ffffffff81e8d9d2-ffffffff81e8d9e6: ioc_timer_fn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ioc_timer_fn(struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2207
Inline: False
```
**Symbols:**

```
ffffffff8176f6d0-ffffffff8177023f: ioc_timer_fn (STB_LOCAL)
ffffffff82076ee8-ffffffff82076efc: ioc_timer_fn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ioc_timer_fn(struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2223
Inline: False
```
**Symbols:**

```
ffffffff817afa00-ffffffff817b0542: ioc_timer_fn (STB_LOCAL)
ffffffff820f6d9c-ffffffff820f6db0: ioc_timer_fn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ioc_timer_fn(struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2230
Inline: False
```
**Symbols:**

```
ffffffff817f3810-ffffffff817f4352: ioc_timer_fn (STB_LOCAL)
ffffffff821d41ea-ffffffff821d41fe: ioc_timer_fn.cold (STB_LOCAL)
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
void ioc_timer_fn(struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffff800010616b30)
Location: block/blk-iocost.c:1341
Inline: False
```
**Symbols:**

```
ffff800010616b30-ffff800010617a54: ioc_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ioc_timer_fn(struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c07c188c)
Location: block/blk-iocost.c:1341
Inline: False
```
**Symbols:**

```
c07c188c-c07c2a90: ioc_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ioc_timer_fn(struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c0000000007b6190)
Location: block/blk-iocost.c:1341
Inline: False
```
**Symbols:**

```
c0000000007b6190-c0000000007b7144: ioc_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ioc_timer_fn(struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffe00044d362)
Location: block/blk-iocost.c:1341
Inline: False
```
**Symbols:**

```
ffffffe00044d362-ffffffe00044e03e: ioc_timer_fn (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void ioc_timer_fn(struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8150add0)
Location: block/blk-iocost.c:1341
Inline: False
```
**Symbols:**

```
ffffffff8150add0-ffffffff8150bbb2: ioc_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ioc_timer_fn(struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff814fb230)
Location: block/blk-iocost.c:1341
Inline: False
```
**Symbols:**

```
ffffffff814fb230-ffffffff814fc006: ioc_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ioc_timer_fn(struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81506e60)
Location: block/blk-iocost.c:1341
Inline: False
```
**Symbols:**

```
ffffffff81506e60-ffffffff81507c42: ioc_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ioc_timer_fn(struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81520310)
Location: block/blk-iocost.c:1341
Inline: False
```
**Symbols:**

```
ffffffff81520310-ffffffff81521152: ioc_timer_fn (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
