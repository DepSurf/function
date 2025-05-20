# Function: <code>FANOTIFY_E</code>

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
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.h:44
Inline: True
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
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.h:44
Inline: True
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
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.h:44
Inline: True
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
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.h:45
Inline: True
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
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.h:50
Inline: True
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
In fs/notify/fanotify/fanotify.c (ffffffff812e7d95)
Location: fs/notify/fanotify/fanotify.h:50
Inline: True
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
In fs/notify/fanotify/fanotify.c (ffffffff812fc9c5)
Location: fs/notify/fanotify/fanotify.h:50
Inline: True
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
In fs/notify/fanotify/fanotify.c (ffffffff8131d385)
Location: fs/notify/fanotify/fanotify.h:137
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131ef53)
Location: fs/notify/fanotify/fanotify.h:137
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
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
In fs/notify/fanotify/fanotify.c (ffffffff813301c5)
Location: fs/notify/fanotify/fanotify.h:137
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81331d03)
Location: fs/notify/fanotify/fanotify.h:137
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
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
In fs/notify/fanotify/fanotify.c (ffffffff8136a315)
Location: fs/notify/fanotify/fanotify.h:185
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify.c:fanotify_merge
  - fs/notify/fanotify/fanotify.c:fanotify_merge
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8136be73)
Location: fs/notify/fanotify/fanotify.h:185
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:get_one_event
  - fs/notify/fanotify/fanotify_user.c:get_one_event
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
In fs/notify/fanotify/fanotify.c (ffffffff81377435)
Location: fs/notify/fanotify/fanotify.h:267
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify.c:fanotify_merge
  - fs/notify/fanotify/fanotify.c:fanotify_merge
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81379713)
Location: fs/notify/fanotify/fanotify.h:267
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:get_one_event
  - fs/notify/fanotify/fanotify_user.c:get_one_event
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
In fs/notify/fanotify/fanotify.c (ffffffff8137dcd5)
Location: fs/notify/fanotify/fanotify.h:285
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify.c:fanotify_insert_event
  - fs/notify/fanotify/fanotify.c:fanotify_merge
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81380280)
Location: fs/notify/fanotify/fanotify.h:285
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
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
In fs/notify/fanotify/fanotify.c (ffffffff813cac15)
Location: fs/notify/fanotify/fanotify.h:285
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify.c:fanotify_insert_event
  - fs/notify/fanotify/fanotify.c:fanotify_merge
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cd995)
Location: fs/notify/fanotify/fanotify.h:285
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
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
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.h:445
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: fs/notify/fanotify/fanotify.h:445
Inline: True
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
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.h:445
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: fs/notify/fanotify/fanotify.h:445
Inline: True
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
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.h:449
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: fs/notify/fanotify/fanotify.h:449
Inline: True
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
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.h:449
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: fs/notify/fanotify/fanotify.h:449
Inline: True
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
In fs/notify/fanotify/fanotify.c (ffff8000103ed328)
Location: fs/notify/fanotify/fanotify.h:137
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffff8000103eefb8)
Location: fs/notify/fanotify/fanotify.h:137
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
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
In fs/notify/fanotify/fanotify.c (c05c3b8c)
Location: fs/notify/fanotify/fanotify.h:137
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (c05c4ae4)
Location: fs/notify/fanotify/fanotify.h:137
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
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
In fs/notify/fanotify/fanotify.c (c0000000004f4970)
Location: fs/notify/fanotify/fanotify.h:137
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (c0000000004f5d68)
Location: fs/notify/fanotify/fanotify.h:137
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
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
In fs/notify/fanotify/fanotify.c (ffffffe0002a0e38)
Location: fs/notify/fanotify/fanotify.h:137
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffe0002a1ed0)
Location: fs/notify/fanotify/fanotify.h:137
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
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
In fs/notify/fanotify/fanotify.c (ffffffff813287a5)
Location: fs/notify/fanotify/fanotify.h:137
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8132a2e3)
Location: fs/notify/fanotify/fanotify.h:137
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
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
In fs/notify/fanotify/fanotify.c (ffffffff81319345)
Location: fs/notify/fanotify/fanotify.h:137
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131ae83)
Location: fs/notify/fanotify/fanotify.h:137
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
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
In fs/notify/fanotify/fanotify.c (ffffffff81326275)
Location: fs/notify/fanotify/fanotify.h:137
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81327db3)
Location: fs/notify/fanotify/fanotify.h:137
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
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
In fs/notify/fanotify/fanotify.c (ffffffff81338095)
Location: fs/notify/fanotify/fanotify.h:137
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81339374)
Location: fs/notify/fanotify/fanotify.h:137
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
</details>
</li>
</ul>

## Differences
