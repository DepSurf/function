# Function: <code>uevent_net_broadcast_tagged</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff819d2471)
Location: lib/kobject_uevent.c:340
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In lib/kobject_uevent.c (ffffffff81a0b879)
Location: lib/kobject_uevent.c:341
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In lib/kobject_uevent.c (ffffffff81a7b205)
Location: lib/kobject_uevent.c:341
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In lib/kobject_uevent.c (ffffffff81ab2565)
Location: lib/kobject_uevent.c:341
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uevent_net_broadcast_tagged(struct sock *usk, struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff815ec3a0)
Location: lib/kobject_uevent.c:341
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff815ec3a0-ffffffff815ec437: uevent_net_broadcast_tagged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uevent_net_broadcast_tagged(struct sock *usk, struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81610b80)
Location: lib/kobject_uevent.c:341
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff81610b80-ffffffff81610c17: uevent_net_broadcast_tagged (STB_LOCAL)
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
In lib/kobject_uevent.c (ffffffff815f42ab)
Location: lib/kobject_uevent.c:342
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
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
In lib/kobject_uevent.c (ffffffff8166161b)
Location: lib/kobject_uevent.c:342
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
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
In lib/kobject_uevent.c (ffffffff8177b3d5)
Location: lib/kobject_uevent.c:342
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
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
In lib/kobject_uevent.c (ffffffff820245e5)
Location: lib/kobject_uevent.c:342
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
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
In lib/kobject_uevent.c (ffffffff820a46f5)
Location: lib/kobject_uevent.c:342
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
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
In lib/kobject_uevent.c (ffffffff8217c7c5)
Location: lib/kobject_uevent.c:342
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
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
In lib/kobject_uevent.c (ffff800010d8c6fc)
Location: lib/kobject_uevent.c:341
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In lib/kobject_uevent.c (c0e86abc)
Location: lib/kobject_uevent.c:341
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In lib/kobject_uevent.c (c000000000ece808)
Location: lib/kobject_uevent.c:341
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In lib/kobject_uevent.c (ffffffe0008b58b8)
Location: lib/kobject_uevent.c:341
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In lib/kobject_uevent.c (ffffffff81a513b5)
Location: lib/kobject_uevent.c:341
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In lib/kobject_uevent.c (ffffffff81a0e4b5)
Location: lib/kobject_uevent.c:341
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In lib/kobject_uevent.c (ffffffff81abd7a5)
Location: lib/kobject_uevent.c:341
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In lib/kobject_uevent.c (ffffffff81ac9c25)
Location: lib/kobject_uevent.c:341
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
