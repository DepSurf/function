# Function: <code>audit_put_parent</code>

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
In kernel/audit_watch.c (ffffffff81129c2c)
Location: kernel/audit_watch.c:89
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch_rule
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
In kernel/audit_watch.c (ffffffff811327cc)
Location: kernel/audit_watch.c:90
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
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
In kernel/audit_watch.c (ffffffff8113c52c)
Location: kernel/audit_watch.c:90
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
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
In kernel/audit_watch.c (ffffffff8113dbb3)
Location: kernel/audit_watch.c:91
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
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
In kernel/audit_watch.c (ffffffff8114a983)
Location: kernel/audit_watch.c:91
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
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
In kernel/audit_watch.c (ffffffff811593e1)
Location: kernel/audit_watch.c:91
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
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
In kernel/audit_watch.c (ffffffff81166381)
Location: kernel/audit_watch.c:91
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
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
In kernel/audit_watch.c (ffffffff81172f00)
Location: kernel/audit_watch.c:78
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
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
In kernel/audit_watch.c (ffffffff8117edb0)
Location: kernel/audit_watch.c:78
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
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
In kernel/audit_watch.c (ffffffff81192299)
Location: kernel/audit_watch.c:78
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_to_parent
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
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
In kernel/audit_watch.c (ffffffff8118f429)
Location: kernel/audit_watch.c:78
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_to_parent
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
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
In kernel/audit_watch.c (ffffffff81190389)
Location: kernel/audit_watch.c:78
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
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
In kernel/audit_watch.c (ffffffff811b9269)
Location: kernel/audit_watch.c:78
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
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
In kernel/audit_watch.c (ffffffff811ec2ae)
Location: kernel/audit_watch.c:78
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
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
In kernel/audit_watch.c (ffffffff8123271e)
Location: kernel/audit_watch.c:78
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
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
In kernel/audit_watch.c (ffffffff8124939e)
Location: kernel/audit_watch.c:78
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
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
In kernel/audit_watch.c (ffffffff8126325e)
Location: kernel/audit_watch.c:78
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
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
In kernel/audit_watch.c (ffff8000101f3ca0)
Location: kernel/audit_watch.c:78
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
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
In kernel/audit_watch.c (c043410c)
Location: kernel/audit_watch.c:78
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
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
In kernel/audit_watch.c (c000000000268c04)
Location: kernel/audit_watch.c:78
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
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
In kernel/audit_watch.c (ffffffe000167034)
Location: kernel/audit_watch.c:78
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
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
In kernel/audit_watch.c (ffffffff811773d0)
Location: kernel/audit_watch.c:78
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
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
In kernel/audit_watch.c (ffffffff8116a570)
Location: kernel/audit_watch.c:78
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
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
In kernel/audit_watch.c (ffffffff811751a0)
Location: kernel/audit_watch.c:78
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
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
In kernel/audit_watch.c (ffffffff81182a80)
Location: kernel/audit_watch.c:78
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
```
</details>
</li>
</ul>

## Differences
