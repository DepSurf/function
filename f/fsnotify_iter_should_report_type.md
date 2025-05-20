# Function: <code>fsnotify_iter_should_report_type</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff812e445d)
Location: include/linux/fsnotify_backend.h:219
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/fanotify/fanotify.c (ffffffff812e7ffe)
Location: include/linux/fsnotify_backend.h:219
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff812f91e0)
Location: include/linux/fsnotify_backend.h:240
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/fanotify/fanotify.c (ffffffff812fccc8)
Location: include/linux/fsnotify_backend.h:240
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81319835)
Location: include/linux/fsnotify_backend.h:245
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8131d908)
Location: include/linux/fsnotify_backend.h:245
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff8132c665)
Location: include/linux/fsnotify_backend.h:245
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81330748)
Location: include/linux/fsnotify_backend.h:245
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81366541)
Location: include/linux/fsnotify_backend.h:271
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:send_to_group
  - fs/notify/fsnotify.c:send_to_group
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8136a120)
Location: include/linux/fsnotify_backend.h:271
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_get_fsid
  - fs/notify/fanotify/fanotify.c:fanotify_group_event_mask
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81373644)
Location: include/linux/fsnotify_backend.h:305
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:send_to_group
  - fs/notify/fsnotify.c:send_to_group
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813781f3)
Location: include/linux/fsnotify_backend.h:305
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_get_fsid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81379fa5)
Location: include/linux/fsnotify_backend.h:302
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:send_to_group
  - fs/notify/fsnotify.c:send_to_group
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8137edb2)
Location: include/linux/fsnotify_backend.h:302
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff813c6bb2)
Location: include/linux/fsnotify_backend.h:302
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:send_to_group
  - fs/notify/fsnotify.c:send_to_group
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813cbe73)
Location: include/linux/fsnotify_backend.h:302
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff8144d6ee)
Location: include/linux/fsnotify_backend.h:407
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:send_to_group
  - fs/notify/fsnotify.c:send_to_group
  - fs/notify/fsnotify.c:send_to_group
  - fs/notify/fsnotify.c:send_to_group
  - fs/notify/fsnotify.c:send_to_group
  - fs/notify/fsnotify.c:send_to_group
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81454497)
Location: include/linux/fsnotify_backend.h:407
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff814dbd09)
Location: include/linux/fsnotify_backend.h:407
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:send_to_group
  - fs/notify/fsnotify.c:send_to_group
  - fs/notify/fsnotify.c:send_to_group
  - fs/notify/fsnotify.c:send_to_group
  - fs/notify/fsnotify.c:send_to_group
  - fs/notify/fsnotify.c:send_to_group
```
```
In fs/notify/fanotify/fanotify.c (ffffffff814e3353)
Location: include/linux/fsnotify_backend.h:407
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff815124f4)
Location: include/linux/fsnotify_backend.h:407
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:send_to_group
  - fs/notify/fsnotify.c:send_to_group
  - fs/notify/fsnotify.c:send_to_group
  - fs/notify/fsnotify.c:send_to_group
  - fs/notify/fsnotify.c:send_to_group
  - fs/notify/fsnotify.c:send_to_group
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81519c6c)
Location: include/linux/fsnotify_backend.h:407
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff815469a4)
Location: include/linux/fsnotify_backend.h:407
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:send_to_group
  - fs/notify/fsnotify.c:send_to_group
  - fs/notify/fsnotify.c:send_to_group
  - fs/notify/fsnotify.c:send_to_group
  - fs/notify/fsnotify.c:send_to_group
  - fs/notify/fsnotify.c:send_to_group
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8154e140)
Location: include/linux/fsnotify_backend.h:407
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffff8000103e7f80)
Location: include/linux/fsnotify_backend.h:245
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/fanotify/fanotify.c (ffff8000103ed948)
Location: include/linux/fsnotify_backend.h:245
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (c05bfaac)
Location: include/linux/fsnotify_backend.h:245
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/fanotify/fanotify.c (c05c41b8)
Location: include/linux/fsnotify_backend.h:245
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (c0000000004eea98)
Location: include/linux/fsnotify_backend.h:245
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/fanotify/fanotify.c (c0000000004f5154)
Location: include/linux/fsnotify_backend.h:245
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffe00029cd26)
Location: include/linux/fsnotify_backend.h:245
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/fanotify/fanotify.c (ffffffe0002a133a)
Location: include/linux/fsnotify_backend.h:245
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81324c45)
Location: include/linux/fsnotify_backend.h:245
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81328d28)
Location: include/linux/fsnotify_backend.h:245
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff813157e5)
Location: include/linux/fsnotify_backend.h:245
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813198c8)
Location: include/linux/fsnotify_backend.h:245
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81322715)
Location: include/linux/fsnotify_backend.h:245
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813267f8)
Location: include/linux/fsnotify_backend.h:245
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81334575)
Location: include/linux/fsnotify_backend.h:245
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81338618)
Location: include/linux/fsnotify_backend.h:245
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
</ul>

## Differences
