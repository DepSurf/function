# Function: <code>path_connected</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool path_connected(const struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81216700)
Location: fs/namei.c:570
Inline: False
Direct callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot
```
**Symbols:**

```
ffffffff81216700-ffffffff8121672f: path_connected (STB_LOCAL)
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
In fs/namei.c (ffffffff8123d7c7)
Location: fs/namei.c:578
Inline: True
Inline callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
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
In fs/namei.c (ffffffff81250567)
Location: fs/namei.c:578
Inline: True
Inline callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
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
In fs/namei.c (ffffffff8125c7b7)
Location: fs/namei.c:578
Inline: True
Inline callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool path_connected(const struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8127ea90)
Location: fs/namei.c:578
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:path_parent_directory
```
**Symbols:**

```
ffffffff8127ea90-ffffffff8127eac1: path_connected (STB_LOCAL)
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
In fs/namei.c (ffffffff812ab03e)
Location: fs/namei.c:562
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:path_parent_directory
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
In fs/namei.c (ffffffff812bb38a)
Location: fs/namei.c:562
Inline: True
Inline callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
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
In fs/namei.c (ffffffff812d7fca)
Location: fs/namei.c:560
Inline: True
Inline callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
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
In fs/namei.c (ffffffff812e9b3a)
Location: fs/namei.c:560
Inline: True
Inline callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
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
In fs/namei.c (ffffffff813286d0)
Location: fs/namei.c:567
Inline: True
Inline callers:
  - fs/namei.c:path_pts
  - fs/namei.c:follow_dotdot
  - fs/namei.c:follow_dotdot_rcu
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
In fs/namei.c (ffffffff81333c2c)
Location: fs/namei.c:567
Inline: True
Inline callers:
  - fs/namei.c:path_pts
  - fs/namei.c:follow_dotdot
  - fs/namei.c:follow_dotdot_rcu
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
In fs/namei.c (ffffffff81339cfc)
Location: fs/namei.c:619
Inline: True
Inline callers:
  - fs/namei.c:path_pts
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
In fs/namei.c (ffffffff81386fac)
Location: fs/namei.c:646
Inline: True
Inline callers:
  - fs/namei.c:path_pts
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
In fs/namei.c (ffffffff81407d4a)
Location: fs/namei.c:647
Inline: True
Inline callers:
  - fs/namei.c:path_pts
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
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
In fs/namei.c (ffffffff8149220a)
Location: fs/namei.c:647
Inline: True
Inline callers:
  - fs/namei.c:path_pts
  - fs/namei.c:handle_dots
  - fs/namei.c:follow_dotdot_rcu
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
In fs/namei.c (ffffffff814c724a)
Location: fs/namei.c:650
Inline: True
Inline callers:
  - fs/namei.c:path_pts
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
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
In fs/namei.c (ffffffff814f9aca)
Location: fs/namei.c:653
Inline: True
Inline callers:
  - fs/namei.c:path_pts
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
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
In fs/namei.c (ffff8000103930bc)
Location: fs/namei.c:560
Inline: True
Inline callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool path_connected(const struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c0579404)
Location: fs/namei.c:560
Inline: False
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
```
**Symbols:**

```
c0579404-c057944c: path_connected (STB_LOCAL)
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
In fs/namei.c (c00000000048c7a0)
Location: fs/namei.c:560
Inline: True
Inline callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
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
In fs/namei.c (ffffffe000262118)
Location: fs/namei.c:560
Inline: True
Inline callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
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
In fs/namei.c (ffffffff812e211a)
Location: fs/namei.c:560
Inline: True
Inline callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
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
In fs/namei.c (ffffffff812d2d5a)
Location: fs/namei.c:560
Inline: True
Inline callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
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
In fs/namei.c (ffffffff812dff2a)
Location: fs/namei.c:560
Inline: True
Inline callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
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
In fs/namei.c (ffffffff812f16ca)
Location: fs/namei.c:560
Inline: True
Inline callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
