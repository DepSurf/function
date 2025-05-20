# Function: <code>dm_softirq_done</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dm_softirq_done(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a1bc0)
Location: drivers/md/dm.c:1303
Inline: False
```
**Symbols:**

```
ffffffff816a1bc0-ffffffff816a1e32: dm_softirq_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dm_softirq_done(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8170f1e0)
Location: drivers/md/dm-rq.c:385
Inline: False
```
**Symbols:**

```
ffffffff8170f1e0-ffffffff8170f452: dm_softirq_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dm_softirq_done(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff817411f0)
Location: drivers/md/dm-rq.c:394
Inline: False
```
**Symbols:**

```
ffffffff817411f0-ffffffff81741443: dm_softirq_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void dm_softirq_done(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8175b190)
Location: drivers/md/dm-rq.c:331
Inline: True
```
**Symbols:**

```
ffffffff8175b190-ffffffff8175b3c5: dm_softirq_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void dm_softirq_done(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff817cd3e0)
Location: drivers/md/dm-rq.c:327
Inline: True
```
**Symbols:**

```
ffffffff817cd3e0-ffffffff817cd61e: dm_softirq_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void dm_softirq_done(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818161e0)
Location: drivers/md/dm-rq.c:331
Inline: True
```
**Symbols:**

```
ffffffff818161e0-ffffffff8181642d: dm_softirq_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void dm_softirq_done(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81841f80)
Location: drivers/md/dm-rq.c:242
Inline: True
```
**Symbols:**

```
ffffffff81841f80-ffffffff8184217e: dm_softirq_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dm_softirq_done(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81884f3b)
Location: drivers/md/dm-rq.c:261
Inline: True
```
**Symbols:**

```
ffffffff81884dd0-ffffffff81884fde: dm_softirq_done (STB_LOCAL)
ffffffff8188521d-ffffffff8188522e: dm_softirq_done.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dm_softirq_done(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818b6ebb)
Location: drivers/md/dm-rq.c:261
Inline: True
```
**Symbols:**

```
ffffffff818b6d50-ffffffff818b6f5e: dm_softirq_done (STB_LOCAL)
ffffffff818b71ae-ffffffff818b71bf: dm_softirq_done.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void dm_softirq_done(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81987840)
Location: drivers/md/dm-rq.c:254
Inline: True
```
**Symbols:**

```
ffffffff81987840-ffffffff8198790b: dm_softirq_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void dm_softirq_done(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8198b7d0)
Location: drivers/md/dm-rq.c:254
Inline: True
```
**Symbols:**

```
ffffffff8198b7d0-ffffffff8198b89b: dm_softirq_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dm_softirq_done(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8196fec0)
Location: drivers/md/dm-rq.c:254
Inline: True
```
**Symbols:**

```
ffffffff8196fec0-ffffffff8196ff8b: dm_softirq_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dm_softirq_done(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81a18783)
Location: drivers/md/dm-rq.c:254
Inline: True
```
**Symbols:**

```
ffffffff81a18600-ffffffff81a1889e: dm_softirq_done (STB_LOCAL)
ffffffff81d2a7e0-ffffffff81d2a7f1: dm_softirq_done.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dm_softirq_done(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81b814f9)
Location: drivers/md/dm-rq.c:250
Inline: True
```
**Symbols:**

```
ffffffff81b81340-ffffffff81b8165e: dm_softirq_done (STB_LOCAL)
ffffffff81ef69c6-ffffffff81ef69d6: dm_softirq_done.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dm_softirq_done(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81d1f680)
Location: drivers/md/dm-rq.c:249
Inline: True
```
**Symbols:**

```
ffffffff81d1f680-ffffffff81d1f9a4: dm_softirq_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dm_softirq_done(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81d88860)
Location: drivers/md/dm-rq.c:251
Inline: True
```
**Symbols:**

```
ffffffff81d88860-ffffffff81d88ba0: dm_softirq_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dm_softirq_done(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81e3ff70)
Location: drivers/md/dm-rq.c:251
Inline: True
```
**Symbols:**

```
ffffffff81e3ff70-ffffffff81e402b0: dm_softirq_done (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void dm_softirq_done(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffff800010b0ed50)
Location: drivers/md/dm-rq.c:261
Inline: True
```
**Symbols:**

```
ffff800010b0ed50-ffff800010b0ef70: dm_softirq_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void dm_softirq_done(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (c0bed13c)
Location: drivers/md/dm-rq.c:261
Inline: True
```
**Symbols:**

```
c0bed13c-c0bed31c: dm_softirq_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void dm_softirq_done(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (c000000000c01fa0)
Location: drivers/md/dm-rq.c:261
Inline: True
```
**Symbols:**

```
c000000000c01fa0-c000000000c022b8: dm_softirq_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void dm_softirq_done(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffe0006fbf8c)
Location: drivers/md/dm-rq.c:261
Inline: True
```
**Symbols:**

```
ffffffe0006fbf8c-ffffffe0006fc130: dm_softirq_done (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dm_softirq_done(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8185cd3b)
Location: drivers/md/dm-rq.c:261
Inline: True
```
**Symbols:**

```
ffffffff8185cbd0-ffffffff8185cdde: dm_softirq_done (STB_LOCAL)
ffffffff8185d02e-ffffffff8185d03f: dm_softirq_done.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dm_softirq_done(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8182430b)
Location: drivers/md/dm-rq.c:261
Inline: True
```
**Symbols:**

```
ffffffff818241a0-ffffffff818243ae: dm_softirq_done (STB_LOCAL)
ffffffff818245fe-ffffffff8182460f: dm_softirq_done.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dm_softirq_done(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818ac36b)
Location: drivers/md/dm-rq.c:261
Inline: True
```
**Symbols:**

```
ffffffff818ac200-ffffffff818ac40e: dm_softirq_done (STB_LOCAL)
ffffffff818ac65e-ffffffff818ac66f: dm_softirq_done.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dm_softirq_done(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818c85bb)
Location: drivers/md/dm-rq.c:261
Inline: True
```
**Symbols:**

```
ffffffff818c8450-ffffffff818c865e: dm_softirq_done (STB_LOCAL)
ffffffff818c88ae-ffffffff818c88bf: dm_softirq_done.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
