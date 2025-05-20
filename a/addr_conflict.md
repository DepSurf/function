# Function: <code>addr_conflict</code>

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
In kernel/jump_label.c (ffffffff8118b3ee)
Location: kernel/jump_label.c:120
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (ffffffff8119dae5)
Location: kernel/jump_label.c:194
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (ffffffff811ad505)
Location: kernel/jump_label.c:201
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (ffffffff811b4a07)
Location: kernel/jump_label.c:207
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (ffffffff811c8927)
Location: kernel/jump_label.c:261
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (ffffffff811e8e77)
Location: kernel/jump_label.c:262
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (ffffffff811f9b75)
Location: kernel/jump_label.c:285
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (ffffffff81211ab6)
Location: kernel/jump_label.c:309
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (ffffffff8121f2b6)
Location: kernel/jump_label.c:309
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (ffffffff8124b576)
Location: kernel/jump_label.c:309
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/static_call.c (ffffffff81239ed7)
Location: kernel/static_call.c:282
Inline: True
Inline callers:
  - kernel/static_call.c:static_call_text_reserved
  - kernel/static_call.c:__static_call_mod_text_reserved
```
```
In kernel/jump_label.c (ffffffff812559c7)
Location: kernel/jump_label.c:309
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:__jump_label_mod_text_reserved
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/static_call.c (ffffffff8123e5fc)
Location: kernel/static_call.c:282
Inline: True
Inline callers:
  - kernel/static_call.c:static_call_text_reserved
  - kernel/static_call.c:static_call_text_reserved
```
```
In kernel/jump_label.c (ffffffff81259ed4)
Location: kernel/jump_label.c:309
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/static_call.c (ffffffff812790dc)
Location: kernel/static_call.c:282
Inline: True
Inline callers:
  - kernel/static_call.c:static_call_text_reserved
  - kernel/static_call.c:static_call_text_reserved
```
```
In kernel/jump_label.c (ffffffff81295c70)
Location: kernel/jump_label.c:309
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/static_call_inline.c (ffffffff812cbf6a)
Location: kernel/static_call_inline.c:282
Inline: True
Inline callers:
  - kernel/static_call_inline.c:static_call_text_reserved
  - kernel/static_call_inline.c:static_call_text_reserved
```
```
In kernel/jump_label.c (ffffffff812eb990)
Location: kernel/jump_label.c:309
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/static_call_inline.c (ffffffff8133395a)
Location: kernel/static_call_inline.c:293
Inline: True
Inline callers:
  - kernel/static_call_inline.c:static_call_text_reserved
  - kernel/static_call_inline.c:static_call_text_reserved
```
```
In kernel/jump_label.c (ffffffff81355a60)
Location: kernel/jump_label.c:337
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/static_call_inline.c (ffffffff8136468e)
Location: kernel/static_call_inline.c:293
Inline: True
Inline callers:
  - kernel/static_call_inline.c:static_call_text_reserved
  - kernel/static_call_inline.c:static_call_text_reserved
```
```
In kernel/jump_label.c (ffffffff813870c7)
Location: kernel/jump_label.c:337
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/static_call_inline.c (ffffffff8138d5be)
Location: kernel/static_call_inline.c:293
Inline: True
Inline callers:
  - kernel/static_call_inline.c:static_call_text_reserved
  - kernel/static_call_inline.c:static_call_text_reserved
```
```
In kernel/jump_label.c (ffffffff813b05d7)
Location: kernel/jump_label.c:337
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (ffff8000102ab774)
Location: kernel/jump_label.c:309
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (c00000000035f94c)
Location: kernel/jump_label.c:309
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (ffffffff81217906)
Location: kernel/jump_label.c:309
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (ffffffff8120a666)
Location: kernel/jump_label.c:309
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (ffffffff812156a6)
Location: kernel/jump_label.c:309
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
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
In kernel/jump_label.c (ffffffff81224696)
Location: kernel/jump_label.c:309
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
</details>
</li>
</ul>

## Differences
