# Function: <code>pipe_lock_nested</code>

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
In fs/pipe.c (ffffffff812149b5)
Location: fs/pipe.c:62
Inline: True
Inline callers:
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_wait
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
In fs/pipe.c (ffffffff8123bbdc)
Location: fs/pipe.c:63
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
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
In fs/pipe.c (ffffffff8124e97c)
Location: fs/pipe.c:63
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
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
In fs/pipe.c (ffffffff8125a8ac)
Location: fs/pipe.c:63
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
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
In fs/pipe.c (ffffffff8127cc3c)
Location: fs/pipe.c:64
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
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
In fs/pipe.c (ffffffff812a3bcc)
Location: fs/pipe.c:59
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
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
In fs/pipe.c (ffffffff812b8d1c)
Location: fs/pipe.c:59
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
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
In fs/pipe.c (ffffffff812d590b)
Location: fs/pipe.c:60
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
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
In fs/pipe.c (ffffffff812e747b)
Location: fs/pipe.c:60
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
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
In fs/pipe.c (ffffffff8131ecee)
Location: fs/pipe.c:63
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8132a20e)
Location: fs/pipe.c:63
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
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
In fs/pipe.c (ffffffff813301be)
Location: fs/pipe.c:78
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
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
In fs/pipe.c (ffffffff8137d97e)
Location: fs/pipe.c:78
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
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
In fs/pipe.c (ffffffff813fe01e)
Location: fs/pipe.c:79
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
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
In fs/pipe.c (ffffffff81487c4e)
Location: fs/pipe.c:79
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
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
In fs/pipe.c (ffffffff814bcb0e)
Location: fs/pipe.c:79
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
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
In fs/pipe.c (ffffffff814eefbe)
Location: fs/pipe.c:79
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
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
In fs/pipe.c (ffff800010390174)
Location: fs/pipe.c:60
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
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
In fs/pipe.c (c0576c10)
Location: fs/pipe.c:60
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
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
In fs/pipe.c (c000000000487bc8)
Location: fs/pipe.c:60
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
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
In fs/pipe.c (ffffffe00025fb86)
Location: fs/pipe.c:60
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
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
In fs/pipe.c (ffffffff812dfa5b)
Location: fs/pipe.c:60
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
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
In fs/pipe.c (ffffffff812d069b)
Location: fs/pipe.c:60
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
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
In fs/pipe.c (ffffffff812dd86b)
Location: fs/pipe.c:60
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
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
In fs/pipe.c (ffffffff812ee7eb)
Location: fs/pipe.c:60
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
  - fs/pipe.c:pipe_double_lock
```
</details>
</li>
</ul>

## Differences
