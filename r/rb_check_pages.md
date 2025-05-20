# Function: <code>rb_check_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rb_check_pages(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811471f0)
Location: kernel/trace/ring_buffer.c:1105
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff811471f0-ffffffff811473a9: rb_check_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rb_check_pages(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8114fa00)
Location: kernel/trace/ring_buffer.c:1096
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff8114fa00-ffffffff8114fbb3: rb_check_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rb_check_pages(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81159c00)
Location: kernel/trace/ring_buffer.c:1094
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff81159c00-ffffffff81159db3: rb_check_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rb_check_pages(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115ca60)
Location: kernel/trace/ring_buffer.c:1096
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff8115ca60-ffffffff8115cb91: rb_check_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rb_check_pages(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81169a00)
Location: kernel/trace/ring_buffer.c:1099
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff81169a00-ffffffff81169b31: rb_check_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rb_check_pages(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81178960)
Location: kernel/trace/ring_buffer.c:1128
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff81178960-ffffffff81178a98: rb_check_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rb_check_pages(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81185e90)
Location: kernel/trace/ring_buffer.c:1176
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff81185e90-ffffffff81185fc8: rb_check_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rb_check_pages(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81193200)
Location: kernel/trace/ring_buffer.c:1153
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff81193200-ffffffff81193388: rb_check_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rb_check_pages(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119ec00)
Location: kernel/trace/ring_buffer.c:1154
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff8119ec00-ffffffff8119ed52: rb_check_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b4e70)
Location: kernel/trace/ring_buffer.c:1156
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff811b4e70-ffffffff811b4f5a: rb_check_pages.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b2930)
Location: kernel/trace/ring_buffer.c:1400
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff811b2930-ffffffff811b2a1a: rb_check_pages.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b3310)
Location: kernel/trace/ring_buffer.c:1483
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff811b3310-ffffffff811b33fa: rb_check_pages.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811dd840)
Location: kernel/trace/ring_buffer.c:1483
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff811dd840-ffffffff811dd92a: rb_check_pages.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81214480)
Location: kernel/trace/ring_buffer.c:1519
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff81214480-ffffffff812145df: rb_check_pages.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8125d550)
Location: kernel/trace/ring_buffer.c:1590
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff8125d550-ffffffff8125d61c: rb_check_pages.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff812747d0)
Location: kernel/trace/ring_buffer.c:1586
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff812747d0-ffffffff8127489c: rb_check_pages.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8128ee40)
Location: kernel/trace/ring_buffer.c:1415
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_subbuf_order_set
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff8128ee40-ffffffff8128ef0c: rb_check_pages.isra.0 (STB_LOCAL)
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
int rb_check_pages(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff8000102196f0)
Location: kernel/trace/ring_buffer.c:1154
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffff8000102196f0-ffff8000102198f4: rb_check_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rb_check_pages(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0456354)
Location: kernel/trace/ring_buffer.c:1154
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
c0456354-c0456580: rb_check_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rb_check_pages(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029a7b0)
Location: kernel/trace/ring_buffer.c:1154
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
c00000000029a7b0-c00000000029aa24: rb_check_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rb_check_pages(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe0001776d0)
Location: kernel/trace/ring_buffer.c:1154
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffe0001776d0-ffffffe0001777e8: rb_check_pages (STB_LOCAL)
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
int rb_check_pages(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81197220)
Location: kernel/trace/ring_buffer.c:1154
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff81197220-ffffffff81197372: rb_check_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rb_check_pages(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118a500)
Location: kernel/trace/ring_buffer.c:1154
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff8118a500-ffffffff8118a652: rb_check_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rb_check_pages(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81194ff0)
Location: kernel/trace/ring_buffer.c:1154
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff81194ff0-ffffffff81195142: rb_check_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rb_check_pages(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a2c00)
Location: kernel/trace/ring_buffer.c:1154
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff811a2c00-ffffffff811a2d52: rb_check_pages (STB_LOCAL)
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
