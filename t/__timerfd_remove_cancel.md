# Function: <code>__timerfd_remove_cancel</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/timerfd.c (ffffffff812a1edb)
Location: fs/timerfd.c:116
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_release
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_release
```
**Symbols:**

```
ffffffff812a1790-ffffffff812a17e7: __timerfd_remove_cancel.part.7 (STB_LOCAL)
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
In fs/timerfd.c (ffffffff812c51fb)
Location: fs/timerfd.c:117
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_release
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_release
```
**Symbols:**

```
ffffffff812c4ab0-ffffffff812c4b07: __timerfd_remove_cancel.part.7 (STB_LOCAL)
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
In fs/timerfd.c (ffffffff812edb02)
Location: fs/timerfd.c:117
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_release
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
In fs/timerfd.c (ffffffff81302592)
Location: fs/timerfd.c:117
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_release
  - fs/timerfd.c:timerfd_release
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
In fs/timerfd.c (ffffffff81323b02)
Location: fs/timerfd.c:117
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_release
  - fs/timerfd.c:timerfd_release
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
In fs/timerfd.c (ffffffff81336862)
Location: fs/timerfd.c:117
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_release
  - fs/timerfd.c:timerfd_release
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
In fs/timerfd.c (ffffffff81370d28)
Location: fs/timerfd.c:118
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_release
  - fs/timerfd.c:timerfd_release
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
In fs/timerfd.c (ffffffff8137eaa0)
Location: fs/timerfd.c:118
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_release
  - fs/timerfd.c:timerfd_release
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
In fs/timerfd.c (ffffffff81385720)
Location: fs/timerfd.c:118
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_release
  - fs/timerfd.c:timerfd_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __timerfd_remove_cancel(struct timerfd_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/timerfd.c (ffffffff813d212c)
Location: fs/timerfd.c:134
Inline: True
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_release
```
**Symbols:**

```
ffffffff813d2100-ffffffff813d2178: __timerfd_remove_cancel (STB_LOCAL)
ffffffff81cc55d1-ffffffff81cc55e6: __timerfd_remove_cancel.cold (STB_LOCAL)
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
In fs/timerfd.c (ffffffff8145b10b)
Location: fs/timerfd.c:134
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_release
  - fs/timerfd.c:timerfd_release
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
In fs/timerfd.c (ffffffff814ea71b)
Location: fs/timerfd.c:134
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_release
  - fs/timerfd.c:timerfd_release
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
In fs/timerfd.c (ffffffff815214be)
Location: fs/timerfd.c:134
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_release
  - fs/timerfd.c:timerfd_release
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
In fs/timerfd.c (ffffffff81555afe)
Location: fs/timerfd.c:134
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_release
  - fs/timerfd.c:timerfd_release
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
In fs/timerfd.c (ffff8000103f45ac)
Location: fs/timerfd.c:117
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_release
  - fs/timerfd.c:timerfd_release
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/timerfd.c (c05c9484)
Location: fs/timerfd.c:117
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_release
Direct callers:
  - fs/timerfd.c:timerfd_release
```
**Symbols:**

```
c05c9404-c05c9464: __timerfd_remove_cancel.part.0 (STB_LOCAL)
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
In fs/timerfd.c (c0000000004fc690)
Location: fs/timerfd.c:117
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_release
  - fs/timerfd.c:timerfd_release
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
In fs/timerfd.c (ffffffe0002a5e56)
Location: fs/timerfd.c:117
Inline: True
Inline callers:
  - fs/timerfd.c:__se_sys_timerfd_settime
  - fs/timerfd.c:__se_sys_timerfd_settime
  - fs/timerfd.c:timerfd_release
  - fs/timerfd.c:timerfd_release
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
In fs/timerfd.c (ffffffff8132ee42)
Location: fs/timerfd.c:117
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_release
  - fs/timerfd.c:timerfd_release
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
In fs/timerfd.c (ffffffff8131fa82)
Location: fs/timerfd.c:117
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_release
  - fs/timerfd.c:timerfd_release
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
In fs/timerfd.c (ffffffff8132c912)
Location: fs/timerfd.c:117
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_release
  - fs/timerfd.c:timerfd_release
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
In fs/timerfd.c (ffffffff8133f672)
Location: fs/timerfd.c:117
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_release
  - fs/timerfd.c:timerfd_release
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
