# Function: <code>link_group</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void link_group(struct config_group *parent_group, struct config_group *group);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff812df800)
Location: fs/configfs/dir.c:779
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff812df800-ffffffff812df86c: link_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void link_group(struct config_group *parent_group, struct config_group *group);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81304180)
Location: fs/configfs/dir.c:779
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff81304180-ffffffff813041ec: link_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void link_group(struct config_group *parent_group, struct config_group *group);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813319b0)
Location: fs/configfs/dir.c:779
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff813319b0-ffffffff81331a1c: link_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void link_group(struct config_group *parent_group, struct config_group *group);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81348da0)
Location: fs/configfs/dir.c:779
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff81348da0-ffffffff81348e0c: link_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void link_group(struct config_group *parent_group, struct config_group *group);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81371360)
Location: fs/configfs/dir.c:798
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff81371360-ffffffff813713cc: link_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void link_group(struct config_group *parent_group, struct config_group *group);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813897b0)
Location: fs/configfs/dir.c:793
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff813897b0-ffffffff8138981c: link_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void link_group(struct config_group *parent_group, struct config_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813d43a0)
Location: fs/configfs/dir.c:793
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:link_group
```
**Symbols:**

```
ffffffff813d43a0-ffffffff813d443f: link_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void link_group(struct config_group *parent_group, struct config_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813e60c0)
Location: fs/configfs/dir.c:794
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:link_group
```
**Symbols:**

```
ffffffff813e60c0-ffffffff813e615f: link_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void link_group(struct config_group *parent_group, struct config_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813eccc0)
Location: fs/configfs/dir.c:792
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:link_group
```
**Symbols:**

```
ffffffff813eccc0-ffffffff813ecd5f: link_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void link_group(struct config_group *parent_group, struct config_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8143ebc0)
Location: fs/configfs/dir.c:775
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:link_group
```
**Symbols:**

```
ffffffff8143ebc0-ffffffff8143ec5f: link_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void link_group(struct config_group *parent_group, struct config_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff814bab40)
Location: fs/configfs/dir.c:775
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:link_group
```
**Symbols:**

```
ffffffff814bab40-ffffffff814babeb: link_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void link_group(struct config_group *parent_group, struct config_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81552420)
Location: fs/configfs/dir.c:777
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:link_group
```
**Symbols:**

```
ffffffff81552420-ffffffff815524cb: link_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void link_group(struct config_group *parent_group, struct config_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8158a170)
Location: fs/configfs/dir.c:777
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:link_group
```
**Symbols:**

```
ffffffff8158a170-ffffffff8158a21b: link_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void link_group(struct config_group *parent_group, struct config_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff815c2e40)
Location: fs/configfs/dir.c:777
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:link_group
```
**Symbols:**

```
ffffffff815c2e40-ffffffff815c2eeb: link_group (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void link_group(struct config_group *parent_group, struct config_group *group);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffff800010459e38)
Location: fs/configfs/dir.c:793
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffff800010459e38-ffff800010459ec4: link_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void link_group(struct config_group *parent_group, struct config_group *group);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c061c134)
Location: fs/configfs/dir.c:793
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
c061c134-c061c1b0: link_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void link_group(struct config_group *parent_group, struct config_group *group);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c000000000575a70)
Location: fs/configfs/dir.c:793
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
c000000000575a70-c000000000575b1c: link_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void link_group(struct config_group *parent_group, struct config_group *group);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffe0002ea9e0)
Location: fs/configfs/dir.c:793
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffe0002ea9e0-ffffffe0002eaa54: link_group (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void link_group(struct config_group *parent_group, struct config_group *group);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81381d90)
Location: fs/configfs/dir.c:793
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff81381d90-ffffffff81381dfc: link_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void link_group(struct config_group *parent_group, struct config_group *group);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81372820)
Location: fs/configfs/dir.c:793
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff81372820-ffffffff8137288c: link_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void link_group(struct config_group *parent_group, struct config_group *group);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8137f860)
Location: fs/configfs/dir.c:793
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff8137f860-ffffffff8137f8cc: link_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void link_group(struct config_group *parent_group, struct config_group *group);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81393a90)
Location: fs/configfs/dir.c:793
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff81393a90-ffffffff81393afc: link_group (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
