# Function: <code>audit_autoremove_mark_rule</code>

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
In kernel/audit_fsnotify.c (ffffffff8112a7c4)
Location: kernel/audit_fsnotify.c:157
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
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
In kernel/audit_fsnotify.c (ffffffff81132998)
Location: kernel/audit_fsnotify.c:157
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
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
In kernel/audit_fsnotify.c (ffffffff8113c6f8)
Location: kernel/audit_fsnotify.c:156
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
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
In kernel/audit_fsnotify.c (ffffffff8113dda6)
Location: kernel/audit_fsnotify.c:156
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
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
In kernel/audit_fsnotify.c (ffffffff8114ab76)
Location: kernel/audit_fsnotify.c:156
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
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
In kernel/audit_fsnotify.c (ffffffff811595cf)
Location: kernel/audit_fsnotify.c:156
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
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
In kernel/audit_fsnotify.c (ffffffff81166569)
Location: kernel/audit_fsnotify.c:154
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
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
In kernel/audit_fsnotify.c (ffffffff8117311b)
Location: kernel/audit_fsnotify.c:145
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
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
In kernel/audit_fsnotify.c (ffffffff8117ef8b)
Location: kernel/audit_fsnotify.c:145
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void audit_autoremove_mark_rule(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff811923f0)
Location: kernel/audit_fsnotify.c:145
Inline: False
Direct callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff811923f0-ffffffff811924a6: audit_autoremove_mark_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void audit_autoremove_mark_rule(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff8118f580)
Location: kernel/audit_fsnotify.c:145
Inline: False
Direct callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff8118f580-ffffffff8118f636: audit_autoremove_mark_rule (STB_LOCAL)
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
In kernel/audit_fsnotify.c (ffffffff8119055f)
Location: kernel/audit_fsnotify.c:145
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
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
In kernel/audit_fsnotify.c (ffffffff811b943f)
Location: kernel/audit_fsnotify.c:145
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
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
In kernel/audit_fsnotify.c (ffffffff811ec4c9)
Location: kernel/audit_fsnotify.c:146
Inline: True
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
In kernel/audit_fsnotify.c (ffffffff81232979)
Location: kernel/audit_fsnotify.c:146
Inline: True
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
In kernel/audit_fsnotify.c (ffffffff812495f9)
Location: kernel/audit_fsnotify.c:146
Inline: True
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
In kernel/audit_fsnotify.c (ffffffff812634e9)
Location: kernel/audit_fsnotify.c:146
Inline: True
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
In kernel/audit_fsnotify.c (ffff8000101f3edc)
Location: kernel/audit_fsnotify.c:145
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
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
In kernel/audit_fsnotify.c (c04342e4)
Location: kernel/audit_fsnotify.c:145
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
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
In kernel/audit_fsnotify.c (c000000000268e8c)
Location: kernel/audit_fsnotify.c:145
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
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
In kernel/audit_fsnotify.c (ffffffe000167256)
Location: kernel/audit_fsnotify.c:145
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
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
In kernel/audit_fsnotify.c (ffffffff811775ab)
Location: kernel/audit_fsnotify.c:145
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
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
In kernel/audit_fsnotify.c (ffffffff8116a74b)
Location: kernel/audit_fsnotify.c:145
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
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
In kernel/audit_fsnotify.c (ffffffff8117537b)
Location: kernel/audit_fsnotify.c:145
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
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
In kernel/audit_fsnotify.c (ffffffff81182c5b)
Location: kernel/audit_fsnotify.c:145
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
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
