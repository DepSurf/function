# Function: <code>dm_build_path_uevent</code>

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
In drivers/md/dm-uevent.c (ffffffff8169fe3a)
Location: drivers/md/dm-uevent.c:71
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
In drivers/md/dm-uevent.c (ffffffff8170123a)
Location: drivers/md/dm-uevent.c:71
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
In drivers/md/dm-uevent.c (ffffffff81732f9a)
Location: drivers/md/dm-uevent.c:71
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
In drivers/md/dm-uevent.c (ffffffff8174bd8a)
Location: drivers/md/dm-uevent.c:71
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
In drivers/md/dm-uevent.c (ffffffff817be10a)
Location: drivers/md/dm-uevent.c:71
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
In drivers/md/dm-uevent.c (ffffffff81806364)
Location: drivers/md/dm-uevent.c:71
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
In drivers/md/dm-uevent.c (ffffffff818324f4)
Location: drivers/md/dm-uevent.c:71
Inline: True
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
In drivers/md/dm-uevent.c (ffffffff81874d08)
Location: drivers/md/dm-uevent.c:58
Inline: True
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
In drivers/md/dm-uevent.c (ffffffff818a6b18)
Location: drivers/md/dm-uevent.c:58
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct dm_uevent *dm_build_path_uevent(struct mapped_device *md, struct dm_target *ti, enum kobject_action action, const char *dm_action, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (0)
Location: drivers/md/dm-uevent.c:58
Inline: False
Direct callers:
  - drivers/md/dm-uevent.c:dm_path_uevent
```
**Symbols:**

```
ffffffff81976910-ffffffff81976a20: dm_build_path_uevent (STB_LOCAL)
ffffffff81976b57-ffffffff81976bf8: dm_build_path_uevent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct dm_uevent *dm_build_path_uevent(struct mapped_device *md, struct dm_target *ti, enum kobject_action action, const char *dm_action, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (0)
Location: drivers/md/dm-uevent.c:58
Inline: False
Direct callers:
  - drivers/md/dm-uevent.c:dm_path_uevent
```
**Symbols:**

```
ffffffff8197b620-ffffffff8197b730: dm_build_path_uevent (STB_LOCAL)
ffffffff81c27f60-ffffffff81c28001: dm_build_path_uevent.cold (STB_LOCAL)
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
In drivers/md/dm-uevent.c (ffffffff8195f8a8)
Location: drivers/md/dm-uevent.c:58
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_path_uevent
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
In drivers/md/dm-uevent.c (ffffffff81a05205)
Location: drivers/md/dm-uevent.c:58
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_path_uevent
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
In drivers/md/dm-uevent.c (ffffffff81b6cf64)
Location: drivers/md/dm-uevent.c:58
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_path_uevent
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
In drivers/md/dm-uevent.c (ffffffff81d090e4)
Location: drivers/md/dm-uevent.c:58
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_path_uevent
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
In drivers/md/dm-uevent.c (ffffffff81d72264)
Location: drivers/md/dm-uevent.c:58
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_path_uevent
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
In drivers/md/dm-uevent.c (ffffffff81e29334)
Location: drivers/md/dm-uevent.c:58
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_path_uevent
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
In drivers/md/dm-uevent.c (ffff800010afbd40)
Location: drivers/md/dm-uevent.c:58
Inline: True
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
In drivers/md/dm-uevent.c (c0bdc274)
Location: drivers/md/dm-uevent.c:58
Inline: True
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
In drivers/md/dm-uevent.c (c000000000be9c48)
Location: drivers/md/dm-uevent.c:58
Inline: True
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
In drivers/md/dm-uevent.c (ffffffe0006ecf0a)
Location: drivers/md/dm-uevent.c:58
Inline: True
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
In drivers/md/dm-uevent.c (ffffffff8184c998)
Location: drivers/md/dm-uevent.c:58
Inline: True
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
In drivers/md/dm-uevent.c (ffffffff81813fb8)
Location: drivers/md/dm-uevent.c:58
Inline: True
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
In drivers/md/dm-uevent.c (ffffffff8189bfc8)
Location: drivers/md/dm-uevent.c:58
Inline: True
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
In drivers/md/dm-uevent.c (ffffffff818b8188)
Location: drivers/md/dm-uevent.c:58
Inline: True
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
