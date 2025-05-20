# Function: <code>cont_expand_zero</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81245628)
Location: fs/buffer.c:2297
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126e3c8)
Location: fs/buffer.c:2353
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81281604)
Location: fs/buffer.c:2394
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128ee34)
Location: fs/buffer.c:2390
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812b1a48)
Location: fs/buffer.c:2350
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d99b1)
Location: fs/buffer.c:2321
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812eeea2)
Location: fs/buffer.c:2333
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813106bc)
Location: fs/buffer.c:2330
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8132369c)
Location: fs/buffer.c:2330
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cont_expand_zero(struct file *file, struct address_space *mapping, loff_t pos, loff_t *bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135a620)
Location: fs/buffer.c:2374
Inline: False
Direct callers:
  - fs/buffer.c:cont_write_begin
```
**Symbols:**

```
ffffffff8135a620-ffffffff8135a907: cont_expand_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cont_expand_zero(struct file *file, struct address_space *mapping, loff_t pos, loff_t *bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813676c0)
Location: fs/buffer.c:2373
Inline: False
Direct callers:
  - fs/buffer.c:cont_write_begin
```
**Symbols:**

```
ffffffff813676c0-ffffffff813678e6: cont_expand_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cont_expand_zero(struct file *file, struct address_space *mapping, loff_t pos, loff_t *bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136e100)
Location: fs/buffer.c:2394
Inline: False
Direct callers:
  - fs/buffer.c:cont_write_begin
```
**Symbols:**

```
ffffffff8136e100-ffffffff8136e322: cont_expand_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cont_expand_zero(struct file *file, struct address_space *mapping, loff_t pos, loff_t *bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:2373
Inline: False
Direct callers:
  - fs/buffer.c:cont_write_begin
```
**Symbols:**

```
ffffffff813bd1c0-ffffffff813bd3f1: cont_expand_zero (STB_LOCAL)
ffffffff81cc4448-ffffffff81cc4468: cont_expand_zero.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cont_expand_zero(struct file *file, struct address_space *mapping, loff_t pos, loff_t *bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:2371
Inline: False
Direct callers:
  - fs/buffer.c:cont_write_begin
```
**Symbols:**

```
ffffffff814433d0-ffffffff8144364c: cont_expand_zero (STB_LOCAL)
ffffffff81e76d72-ffffffff81e76da2: cont_expand_zero.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int cont_expand_zero(struct file *file, struct address_space *mapping, loff_t pos, loff_t *bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:2359
Inline: False
Direct callers:
  - fs/buffer.c:cont_write_begin
```
**Symbols:**

```
ffffffff814d2980-ffffffff814d2bfc: cont_expand_zero (STB_LOCAL)
ffffffff82068f92-ffffffff82068fc2: cont_expand_zero.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int cont_expand_zero(struct file *file, struct address_space *mapping, loff_t pos, loff_t *bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:2500
Inline: False
Direct callers:
  - fs/buffer.c:cont_write_begin
```
**Symbols:**

```
ffffffff81509290-ffffffff81509509: cont_expand_zero (STB_LOCAL)
ffffffff820e88b4-ffffffff820e88e4: cont_expand_zero.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int cont_expand_zero(struct file *file, struct address_space *mapping, loff_t pos, loff_t *bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:2468
Inline: False
Direct callers:
  - fs/buffer.c:cont_write_begin
```
**Symbols:**

```
ffffffff8153e1b0-ffffffff8153e429: cont_expand_zero (STB_LOCAL)
ffffffff821c56b3-ffffffff821c56e3: cont_expand_zero.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103dca10)
Location: fs/buffer.c:2330
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b5e5c)
Location: fs/buffer.c:2330
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004e1f70)
Location: fs/buffer.c:2330
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000294c7a)
Location: fs/buffer.c:2330
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131bc7c)
Location: fs/buffer.c:2330
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130c81c)
Location: fs/buffer.c:2330
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131974c)
Location: fs/buffer.c:2330
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8132b3bf)
Location: fs/buffer.c:2330
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
</details>
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
