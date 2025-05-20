# Function: <code>sbitmap_add_wait_queue</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void sbitmap_add_wait_queue(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8150cb70)
Location: lib/sbitmap.c:667
Inline: False
```
**Symbols:**

```
ffffffff8150cb70-ffffffff8150cb95: sbitmap_add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sbitmap_add_wait_queue(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8153b2e0)
Location: lib/sbitmap.c:663
Inline: False
```
**Symbols:**

```
ffffffff8153b2e0-ffffffff8153b312: sbitmap_add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_add_wait_queue(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8155c330)
Location: lib/sbitmap.c:663
Inline: True
```
**Symbols:**

```
ffffffff8155c330-ffffffff8155c357: sbitmap_add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_add_wait_queue(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815e5bf0)
Location: lib/sbitmap.c:646
Inline: True
```
**Symbols:**

```
ffffffff815e5bf0-ffffffff815e5c17: sbitmap_add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_add_wait_queue(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81609fb0)
Location: lib/sbitmap.c:641
Inline: True
```
**Symbols:**

```
ffffffff81609fb0-ffffffff81609fd7: sbitmap_add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_add_wait_queue(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815ed040)
Location: lib/sbitmap.c:667
Inline: True
```
**Symbols:**

```
ffffffff815ed040-ffffffff815ed064: sbitmap_add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_add_wait_queue(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8165a010)
Location: lib/sbitmap.c:667
Inline: True
```
**Symbols:**

```
ffffffff8165a010-ffffffff8165a034: sbitmap_add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_add_wait_queue(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81772a10)
Location: lib/sbitmap.c:776
Inline: True
```
**Symbols:**

```
ffffffff81772a10-ffffffff81772a48: sbitmap_add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_add_wait_queue(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff818a3030)
Location: lib/sbitmap.c:734
Inline: True
```
**Symbols:**

```
ffffffff818a3030-ffffffff818a306b: sbitmap_add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_add_wait_queue(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff818e5510)
Location: lib/sbitmap.c:726
Inline: True
```
**Symbols:**

```
ffffffff818e5510-ffffffff818e554b: sbitmap_add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_add_wait_queue(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8192c510)
Location: lib/sbitmap.c:721
Inline: True
```
**Symbols:**

```
ffffffff8192c510-ffffffff8192c54b: sbitmap_add_wait_queue (STB_GLOBAL)
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
void sbitmap_add_wait_queue(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffff80001066a0e0)
Location: lib/sbitmap.c:663
Inline: True
```
**Symbols:**

```
ffff80001066a0e0-ffff80001066a130: sbitmap_add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_add_wait_queue(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (c0811edc)
Location: lib/sbitmap.c:663
Inline: True
```
**Symbols:**

```
c0811edc-c0811f28: sbitmap_add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_add_wait_queue(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (c00000000081f610)
Location: lib/sbitmap.c:663
Inline: True
```
**Symbols:**

```
c00000000081f610-c00000000081f66c: sbitmap_add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sbitmap_add_wait_queue(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffe000494414)
Location: lib/sbitmap.c:663
Inline: False
```
**Symbols:**

```
ffffffe000494414-ffffffe000494448: sbitmap_add_wait_queue (STB_GLOBAL)
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
void sbitmap_add_wait_queue(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81554920)
Location: lib/sbitmap.c:663
Inline: True
```
**Symbols:**

```
ffffffff81554920-ffffffff81554947: sbitmap_add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_add_wait_queue(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81544ba0)
Location: lib/sbitmap.c:663
Inline: True
```
**Symbols:**

```
ffffffff81544ba0-ffffffff81544bc7: sbitmap_add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_add_wait_queue(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81550660)
Location: lib/sbitmap.c:663
Inline: True
```
**Symbols:**

```
ffffffff81550660-ffffffff81550687: sbitmap_add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_add_wait_queue(struct sbitmap_queue *sbq, struct sbq_wait_state *ws, struct sbq_wait *sbq_wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8156a4a0)
Location: lib/sbitmap.c:663
Inline: True
```
**Symbols:**

```
ffffffff8156a4a0-ffffffff8156a4c7: sbitmap_add_wait_queue (STB_GLOBAL)
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
