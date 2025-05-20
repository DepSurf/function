# Function: <code>__jump_label_mod_text_reserved</code>

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
In kernel/jump_label.c (ffffffff8118b40e)
Location: kernel/jump_label.c:253
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (ffffffff8119db08)
Location: kernel/jump_label.c:339
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (ffffffff811ad528)
Location: kernel/jump_label.c:346
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (ffffffff811b4a30)
Location: kernel/jump_label.c:407
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (ffffffff811c8950)
Location: kernel/jump_label.c:461
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (ffffffff811e8e9c)
Location: kernel/jump_label.c:479
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (ffffffff811f9ba1)
Location: kernel/jump_label.c:483
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (ffffffff81211ad7)
Location: kernel/jump_label.c:537
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (ffffffff8121f2d7)
Location: kernel/jump_label.c:539
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8124b597)
Location: kernel/jump_label.c:539
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __jump_label_mod_text_reserved(void *start, void *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81254ed0)
Location: kernel/jump_label.c:547
Inline: False
Direct callers:
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffffffff81254ed0-ffffffff81254f7f: __jump_label_mod_text_reserved (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81259efa)
Location: kernel/jump_label.c:549
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81295ca1)
Location: kernel/jump_label.c:550
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812eb9cf)
Location: kernel/jump_label.c:550
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81355a9f)
Location: kernel/jump_label.c:574
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff813870f8)
Location: kernel/jump_label.c:574
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff813b0608)
Location: kernel/jump_label.c:574
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (ffff8000102ab7a4)
Location: kernel/jump_label.c:539
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (c00000000035f970)
Location: kernel/jump_label.c:539
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/jump_label.c (ffffffff81217927)
Location: kernel/jump_label.c:539
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (ffffffff8120a687)
Location: kernel/jump_label.c:539
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (ffffffff812156c7)
Location: kernel/jump_label.c:539
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (ffffffff812246b7)
Location: kernel/jump_label.c:539
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
