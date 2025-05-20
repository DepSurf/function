# Function: <code>__static_key_slow_dec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __static_key_slow_dec(struct static_key *key, long unsigned int rate_limit, struct delayed_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8118af50)
Location: kernel/jump_label.c:72
Inline: True
Direct callers:
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:static_key_slow_dec_deferred
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff8118af50-ffffffff8118afda: __static_key_slow_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __static_key_slow_dec(struct static_key *key, long unsigned int rate_limit, struct delayed_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8119d610)
Location: kernel/jump_label.c:139
Inline: True
Direct callers:
  - kernel/jump_label.c:static_key_slow_dec_deferred
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff8119d610-ffffffff8119d69a: __static_key_slow_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __static_key_slow_dec(struct static_key *key, long unsigned int rate_limit, struct delayed_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811ad030)
Location: kernel/jump_label.c:139
Inline: True
Direct callers:
  - kernel/jump_label.c:static_key_slow_dec_deferred
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff811ad030-ffffffff811ad0ba: __static_key_slow_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __static_key_slow_dec(struct static_key *key, long unsigned int rate_limit, struct delayed_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811b44c0)
Location: kernel/jump_label.c:142
Inline: True
Direct callers:
  - kernel/jump_label.c:static_key_slow_dec_deferred
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff811b44c0-ffffffff811b4552: __static_key_slow_dec (STB_LOCAL)
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
In kernel/jump_label.c (ffffffff811c83dc)
Location: kernel/jump_label.c:209
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec_deferred
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
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
In kernel/jump_label.c (ffffffff811e87ec)
Location: kernel/jump_label.c:210
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec_deferred
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
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
In kernel/jump_label.c (ffffffff811f94bc)
Location: kernel/jump_label.c:233
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec_deferred
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
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
In kernel/jump_label.c (ffffffff81211447)
Location: kernel/jump_label.c:252
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
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
In kernel/jump_label.c (ffffffff8121f087)
Location: kernel/jump_label.c:252
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
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
In kernel/jump_label.c (ffffffff8124ae97)
Location: kernel/jump_label.c:252
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
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
In kernel/jump_label.c (ffffffff81255287)
Location: kernel/jump_label.c:252
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
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
In kernel/jump_label.c (ffffffff81259787)
Location: kernel/jump_label.c:252
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
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
In kernel/jump_label.c (ffffffff812954c4)
Location: kernel/jump_label.c:252
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
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
In kernel/jump_label.c (ffffffff812eb2a7)
Location: kernel/jump_label.c:252
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
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
In kernel/jump_label.c (ffffffff81355347)
Location: kernel/jump_label.c:280
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
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
In kernel/jump_label.c (ffffffff81386837)
Location: kernel/jump_label.c:280
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
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
In kernel/jump_label.c (ffffffff813afcf7)
Location: kernel/jump_label.c:280
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
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
In kernel/jump_label.c (ffff8000102ab434)
Location: kernel/jump_label.c:252
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
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
In kernel/jump_label.c (c00000000035f0d8)
Location: kernel/jump_label.c:252
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
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
In kernel/jump_label.c (ffffffff812176d7)
Location: kernel/jump_label.c:252
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
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
In kernel/jump_label.c (ffffffff8120a437)
Location: kernel/jump_label.c:252
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
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
In kernel/jump_label.c (ffffffff81215477)
Location: kernel/jump_label.c:252
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
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
In kernel/jump_label.c (ffffffff81224467)
Location: kernel/jump_label.c:252
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
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
</ul>
