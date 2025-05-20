# Function: <code>cont_flush</code>

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
In kernel/printk/printk.c (ffffffff810d6f90)
Location: kernel/printk/printk.c:1569
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff810d6f90-ffffffff810d7038: cont_flush.part.14 (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff810dd1eb)
Location: kernel/printk/printk.c:1646
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff810dbee0-ffffffff810dbf87: cont_flush.part.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cont_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e2cd0)
Location: kernel/printk/printk.c:1593
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff810e2cd0-ffffffff810e2d2c: cont_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cont_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e1d90)
Location: kernel/printk/printk.c:1620
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff810e1d90-ffffffff810e1de5: cont_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cont_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e9e90)
Location: kernel/printk/printk.c:1608
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff810e9e90-ffffffff810e9ee5: cont_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cont_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f2120)
Location: kernel/printk/printk.c:1752
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff810f2120-ffffffff810f2174: cont_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cont_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fd7a0)
Location: kernel/printk/printk.c:1771
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:cont_add
  - kernel/printk/printk.c:cont_add
```
**Symbols:**

```
ffffffff810fd7a0-ffffffff810fd7f4: cont_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cont_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811061f0)
Location: kernel/printk/printk.c:1821
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:cont_add
  - kernel/printk/printk.c:cont_add
```
**Symbols:**

```
ffffffff811061f0-ffffffff81106244: cont_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cont_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81112580)
Location: kernel/printk/printk.c:1831
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:cont_add
  - kernel/printk/printk.c:cont_add
```
**Symbols:**

```
ffffffff81112580-ffffffff811125d4: cont_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cont_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111dda0)
Location: kernel/printk/printk.c:1856
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:cont_add
  - kernel/printk/printk.c:cont_add
```
**Symbols:**

```
ffffffff8111dda0-ffffffff8111ddf4: cont_flush (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void cont_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff800010172700)
Location: kernel/printk/printk.c:1831
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:cont_add
  - kernel/printk/printk.c:cont_add
```
**Symbols:**

```
ffff800010172700-ffff800010172758: cont_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cont_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c5420)
Location: kernel/printk/printk.c:1831
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:cont_add
  - kernel/printk/printk.c:cont_add
```
**Symbols:**

```
c03c5420-c03c5490: cont_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cont_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001cbf60)
Location: kernel/printk/printk.c:1831
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:cont_add
  - kernel/printk/printk.c:cont_add
```
**Symbols:**

```
c0000000001cbf60-c0000000001cbfe8: cont_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cont_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffe00010eae0)
Location: kernel/printk/printk.c:1831
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffe00010eae0-ffffffe00010eb34: cont_flush (STB_LOCAL)
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
void cont_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110ab60)
Location: kernel/printk/printk.c:1831
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:cont_add
  - kernel/printk/printk.c:cont_add
```
**Symbols:**

```
ffffffff8110ab60-ffffffff8110abb4: cont_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cont_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fbb10)
Location: kernel/printk/printk.c:1831
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:cont_add
  - kernel/printk/printk.c:cont_add
```
**Symbols:**

```
ffffffff810fbb10-ffffffff810fbb64: cont_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cont_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81108a50)
Location: kernel/printk/printk.c:1831
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:cont_add
  - kernel/printk/printk.c:cont_add
```
**Symbols:**

```
ffffffff81108a50-ffffffff81108aa4: cont_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cont_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81113df0)
Location: kernel/printk/printk.c:1831
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:cont_add
  - kernel/printk/printk.c:cont_add
```
**Symbols:**

```
ffffffff81113df0-ffffffff81113e44: cont_flush (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
