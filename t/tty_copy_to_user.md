# Function: <code>tty_copy_to_user</code>

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
In drivers/tty/n_tty.c (ffffffff814e6482)
Location: drivers/tty/n_tty.c:165
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff8153731e)
Location: drivers/tty/n_tty.c:154
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff81563a3e)
Location: drivers/tty/n_tty.c:154
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff81578e39)
Location: drivers/tty/n_tty.c:154
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff815dd7cc)
Location: drivers/tty/n_tty.c:152
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff81616abd)
Location: drivers/tty/n_tty.c:155
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff81633c15)
Location: drivers/tty/n_tty.c:165
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff816669e8)
Location: drivers/tty/n_tty.c:167
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff81688ce7)
Location: drivers/tty/n_tty.c:167
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tty_copy_to_user(struct tty_struct *tty, void *to, size_t tail, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff8173a290)
Location: drivers/tty/n_tty.c:167
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
```
**Symbols:**

```
ffffffff8173a290-ffffffff8173a3b9: tty_copy_to_user (STB_LOCAL)
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffff80001085652c)
Location: drivers/tty/n_tty.c:167
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (c0960c4c)
Location: drivers/tty/n_tty.c:167
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (c0000000008f8074)
Location: drivers/tty/n_tty.c:167
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffe0005337d4)
Location: drivers/tty/n_tty.c:167
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff8164e767)
Location: drivers/tty/n_tty.c:167
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff8162ebb7)
Location: drivers/tty/n_tty.c:167
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff8167cb27)
Location: drivers/tty/n_tty.c:167
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff81697187)
Location: drivers/tty/n_tty.c:167
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
