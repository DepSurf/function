# Function: <code>copy_to_high_bio_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bounce.c (ffffffff813d5260)
Location: block/bounce.c:102
Inline: True
Direct callers:
  - block/bounce.c:bounce_end_io_read_isa
  - block/bounce.c:bounce_end_io_read
```
**Symbols:**

```
ffffffff813d5260-ffffffff813d53cd: copy_to_high_bio_irq.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bounce.c (ffffffff8141af20)
Location: block/bounce.c:102
Inline: True
Direct callers:
  - block/bounce.c:bounce_end_io_read_isa
  - block/bounce.c:bounce_end_io_read
```
**Symbols:**

```
ffffffff8141af20-ffffffff8141b090: copy_to_high_bio_irq.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bounce.c (ffffffff81436460)
Location: block/bounce.c:102
Inline: True
Direct callers:
  - block/bounce.c:bounce_end_io_read_isa
  - block/bounce.c:bounce_end_io_read
```
**Symbols:**

```
ffffffff81436460-ffffffff814365cc: copy_to_high_bio_irq.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bounce.c (ffffffff81442ac0)
Location: block/bounce.c:112
Inline: True
Direct callers:
  - block/bounce.c:bounce_end_io_read_isa
  - block/bounce.c:bounce_end_io_read
```
**Symbols:**

```
ffffffff81442ac0-ffffffff81442c14: copy_to_high_bio_irq.isra.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bounce.c (ffffffff8146f530)
Location: block/bounce.c:113
Inline: True
Direct callers:
  - block/bounce.c:bounce_end_io_read_isa
  - block/bounce.c:bounce_end_io_read
```
**Symbols:**

```
ffffffff8146f530-ffffffff8146f684: copy_to_high_bio_irq.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void copy_to_high_bio_irq(struct bio *to, struct bio *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff814a3740)
Location: block/bounce.c:113
Inline: False
Direct callers:
  - block/bounce.c:bounce_end_io_read_isa
  - block/bounce.c:bounce_end_io_read
```
**Symbols:**

```
ffffffff814a3740-ffffffff814a39ad: copy_to_high_bio_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void copy_to_high_bio_irq(struct bio *to, struct bio *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff814bddf0)
Location: block/bounce.c:132
Inline: False
Direct callers:
  - block/bounce.c:bounce_end_io_read_isa
  - block/bounce.c:bounce_end_io_read
```
**Symbols:**

```
ffffffff814bddf0-ffffffff814be05e: copy_to_high_bio_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void copy_to_high_bio_irq(struct bio *to, struct bio *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff814ec310)
Location: block/bounce.c:132
Inline: False
Direct callers:
  - block/bounce.c:bounce_end_io_read_isa
  - block/bounce.c:bounce_end_io_read
```
**Symbols:**

```
ffffffff814ec310-ffffffff814ec5cf: copy_to_high_bio_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void copy_to_high_bio_irq(struct bio *to, struct bio *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff81505760)
Location: block/bounce.c:132
Inline: False
Direct callers:
  - block/bounce.c:bounce_end_io_read_isa
  - block/bounce.c:bounce_end_io_read
```
**Symbols:**

```
ffffffff81505760-ffffffff81505a1f: copy_to_high_bio_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void copy_to_high_bio_irq(struct bio *to, struct bio *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff81566350)
Location: block/bounce.c:132
Inline: False
Direct callers:
  - block/bounce.c:bounce_end_io_read_isa
  - block/bounce.c:bounce_end_io_read
```
**Symbols:**

```
ffffffff81566350-ffffffff815665df: copy_to_high_bio_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void copy_to_high_bio_irq(struct bio *to, struct bio *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff815812d0)
Location: block/bounce.c:132
Inline: False
Direct callers:
  - block/bounce.c:bounce_end_io_read_isa
  - block/bounce.c:bounce_end_io_read
```
**Symbols:**

```
ffffffff815812d0-ffffffff81581516: copy_to_high_bio_irq (STB_LOCAL)
```
</details>
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void copy_to_high_bio_irq(struct bio *to, struct bio *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (c07b2aac)
Location: block/bounce.c:132
Inline: False
Direct callers:
  - block/bounce.c:bounce_end_io_read_isa
  - block/bounce.c:bounce_end_io_read
```
**Symbols:**

```
c07b2aac-c07b2d94: copy_to_high_bio_irq (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void copy_to_high_bio_irq(struct bio *to, struct bio *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff814fdd40)
Location: block/bounce.c:132
Inline: False
Direct callers:
  - block/bounce.c:bounce_end_io_read_isa
  - block/bounce.c:bounce_end_io_read
```
**Symbols:**

```
ffffffff814fdd40-ffffffff814fdfff: copy_to_high_bio_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void copy_to_high_bio_irq(struct bio *to, struct bio *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff814ee250)
Location: block/bounce.c:132
Inline: False
Direct callers:
  - block/bounce.c:bounce_end_io_read_isa
  - block/bounce.c:bounce_end_io_read
```
**Symbols:**

```
ffffffff814ee250-ffffffff814ee50f: copy_to_high_bio_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void copy_to_high_bio_irq(struct bio *to, struct bio *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff814f9dd0)
Location: block/bounce.c:132
Inline: False
Direct callers:
  - block/bounce.c:bounce_end_io_read_isa
  - block/bounce.c:bounce_end_io_read
```
**Symbols:**

```
ffffffff814f9dd0-ffffffff814fa08f: copy_to_high_bio_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void copy_to_high_bio_irq(struct bio *to, struct bio *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff81512e30)
Location: block/bounce.c:132
Inline: False
Direct callers:
  - block/bounce.c:bounce_end_io_read_isa
  - block/bounce.c:bounce_end_io_read
```
**Symbols:**

```
ffffffff81512e30-ffffffff815130ef: copy_to_high_bio_irq (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
