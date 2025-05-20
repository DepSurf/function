# Function: <code>__static_call_key</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/static_call.c (ffffffff812397bd)
Location: kernel/static_call.c:38
Inline: True
Inline callers:
  - kernel/static_call.c:static_call_del_module
  - kernel/static_call.c:static_call_add_module
  - kernel/static_call.c:__static_call_update
  - kernel/static_call.c:__static_call_update
  - kernel/static_call.c:__static_call_update
  - kernel/static_call.c:static_call_site_cmp
  - kernel/static_call.c:static_call_site_cmp
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
In kernel/static_call.c (ffffffff8123e5ee)
Location: kernel/static_call.c:38
Inline: True
Inline callers:
  - kernel/static_call.c:static_call_text_reserved
  - kernel/static_call.c:static_call_text_reserved
  - kernel/static_call.c:static_call_module_notify
  - kernel/static_call.c:static_call_del_module
  - kernel/static_call.c:__static_call_update
  - kernel/static_call.c:__static_call_update
  - kernel/static_call.c:__static_call_update
  - kernel/static_call.c:static_call_site_cmp
  - kernel/static_call.c:static_call_site_cmp
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
In kernel/static_call.c (ffffffff812790ce)
Location: kernel/static_call.c:38
Inline: True
Inline callers:
  - kernel/static_call.c:static_call_text_reserved
  - kernel/static_call.c:static_call_text_reserved
  - kernel/static_call.c:static_call_module_notify
  - kernel/static_call.c:static_call_del_module
  - kernel/static_call.c:__static_call_update
  - kernel/static_call.c:__static_call_update
  - kernel/static_call.c:__static_call_update
  - kernel/static_call.c:static_call_site_cmp
  - kernel/static_call.c:static_call_site_cmp
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
In kernel/static_call_inline.c (ffffffff812cbf5c)
Location: kernel/static_call_inline.c:38
Inline: True
Inline callers:
  - kernel/static_call_inline.c:static_call_text_reserved
  - kernel/static_call_inline.c:static_call_text_reserved
  - kernel/static_call_inline.c:static_call_module_notify
  - kernel/static_call_inline.c:static_call_del_module
  - kernel/static_call_inline.c:__static_call_init
  - kernel/static_call_inline.c:__static_call_init
  - kernel/static_call_inline.c:__static_call_update
  - kernel/static_call_inline.c:__static_call_update
  - kernel/static_call_inline.c:__static_call_update
  - kernel/static_call_inline.c:static_call_site_cmp
  - kernel/static_call_inline.c:static_call_site_cmp
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
In kernel/static_call_inline.c (ffffffff8133394c)
Location: kernel/static_call_inline.c:49
Inline: True
Inline callers:
  - kernel/static_call_inline.c:static_call_text_reserved
  - kernel/static_call_inline.c:static_call_text_reserved
  - kernel/static_call_inline.c:static_call_module_notify
  - kernel/static_call_inline.c:static_call_del_module
  - kernel/static_call_inline.c:__static_call_init
  - kernel/static_call_inline.c:__static_call_init
  - kernel/static_call_inline.c:__static_call_update
  - kernel/static_call_inline.c:__static_call_update
  - kernel/static_call_inline.c:__static_call_update
  - kernel/static_call_inline.c:static_call_site_cmp
  - kernel/static_call_inline.c:static_call_site_cmp
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
In kernel/static_call_inline.c (ffffffff813646ee)
Location: kernel/static_call_inline.c:49
Inline: True
Inline callers:
  - kernel/static_call_inline.c:static_call_text_reserved
  - kernel/static_call_inline.c:static_call_text_reserved
  - kernel/static_call_inline.c:static_call_module_notify
  - kernel/static_call_inline.c:static_call_del_module
  - kernel/static_call_inline.c:__static_call_init
  - kernel/static_call_inline.c:__static_call_init
  - kernel/static_call_inline.c:__static_call_init
  - kernel/static_call_inline.c:__static_call_update
  - kernel/static_call_inline.c:__static_call_update
  - kernel/static_call_inline.c:__static_call_update
  - kernel/static_call_inline.c:static_call_site_cmp
  - kernel/static_call_inline.c:static_call_site_cmp
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
In kernel/static_call_inline.c (ffffffff8138d61e)
Location: kernel/static_call_inline.c:49
Inline: True
Inline callers:
  - kernel/static_call_inline.c:static_call_text_reserved
  - kernel/static_call_inline.c:static_call_text_reserved
  - kernel/static_call_inline.c:static_call_module_notify
  - kernel/static_call_inline.c:static_call_del_module
  - kernel/static_call_inline.c:__static_call_init
  - kernel/static_call_inline.c:__static_call_init
  - kernel/static_call_inline.c:__static_call_init
  - kernel/static_call_inline.c:__static_call_update
  - kernel/static_call_inline.c:__static_call_update
  - kernel/static_call_inline.c:__static_call_update
  - kernel/static_call_inline.c:static_call_site_cmp
  - kernel/static_call_inline.c:static_call_site_cmp
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
