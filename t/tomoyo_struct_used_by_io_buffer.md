# Function: <code>tomoyo_struct_used_by_io_buffer</code>

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
In security/tomoyo/gc.c (ffffffff81370182)
Location: security/tomoyo/gc.c:39
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
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
In security/tomoyo/gc.c (ffffffff813a6559)
Location: security/tomoyo/gc.c:39
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
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
In security/tomoyo/gc.c (ffffffff813bd0d9)
Location: security/tomoyo/gc.c:39
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
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
In security/tomoyo/gc.c (ffffffff813d3a3c)
Location: security/tomoyo/gc.c:39
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
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
In security/tomoyo/gc.c (ffffffff813f9f4c)
Location: security/tomoyo/gc.c:40
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
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
In security/tomoyo/gc.c (ffffffff8142aee9)
Location: security/tomoyo/gc.c:40
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
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
In security/tomoyo/gc.c (ffffffff814477d9)
Location: security/tomoyo/gc.c:40
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
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
In security/tomoyo/gc.c (ffffffff814753e9)
Location: security/tomoyo/gc.c:40
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
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
In security/tomoyo/gc.c (ffffffff8148f189)
Location: security/tomoyo/gc.c:40
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tomoyo_struct_used_by_io_buffer(const struct list_head *element);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff814e62c0)
Location: security/tomoyo/gc.c:40
Inline: False
Direct callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
**Symbols:**

```
ffffffff814e62c0-ffffffff814e63a6: tomoyo_struct_used_by_io_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tomoyo_struct_used_by_io_buffer(const struct list_head *element);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff815036c0)
Location: security/tomoyo/gc.c:40
Inline: False
Direct callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
**Symbols:**

```
ffffffff815036c0-ffffffff815037a6: tomoyo_struct_used_by_io_buffer (STB_LOCAL)
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
In security/tomoyo/gc.c (ffffffff8150a3f9)
Location: security/tomoyo/gc.c:40
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
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
In security/tomoyo/gc.c (ffffffff81567a89)
Location: security/tomoyo/gc.c:40
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
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
In security/tomoyo/gc.c (ffffffff81603672)
Location: security/tomoyo/gc.c:40
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
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
In security/tomoyo/gc.c (ffffffff816b4832)
Location: security/tomoyo/gc.c:40
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
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
In security/tomoyo/gc.c (ffffffff816ed32c)
Location: security/tomoyo/gc.c:40
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
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
In security/tomoyo/gc.c (ffffffff8172a0fc)
Location: security/tomoyo/gc.c:40
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
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
In security/tomoyo/gc.c (ffff800010582d04)
Location: security/tomoyo/gc.c:40
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
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
In security/tomoyo/gc.c (c0734c98)
Location: security/tomoyo/gc.c:40
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
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
In security/tomoyo/gc.c (c0000000006f18b0)
Location: security/tomoyo/gc.c:40
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
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
In security/tomoyo/gc.c (ffffffe0003d3080)
Location: security/tomoyo/gc.c:40
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
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
In security/tomoyo/gc.c (ffffffff81487769)
Location: security/tomoyo/gc.c:40
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
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
In security/tomoyo/gc.c (ffffffff81478189)
Location: security/tomoyo/gc.c:40
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
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
In security/tomoyo/gc.c (ffffffff81483809)
Location: security/tomoyo/gc.c:40
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
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
In security/tomoyo/gc.c (ffffffff8149b38e)
Location: security/tomoyo/gc.c:40
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
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
</ul>
