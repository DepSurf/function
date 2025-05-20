# Function: <code>remove_and_add_spares</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int remove_and_add_spares(struct mddev *mddev, struct md_rdev *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81695260)
Location: drivers/md/md.c:8138
Inline: False
Direct callers:
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81695260-ffffffff8169559d: remove_and_add_spares (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int remove_and_add_spares(struct mddev *mddev, struct md_rdev *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff816f6110)
Location: drivers/md/md.c:8187
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
```
**Symbols:**

```
ffffffff816f6110-ffffffff816f64f7: remove_and_add_spares (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int remove_and_add_spares(struct mddev *mddev, struct md_rdev *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81727950)
Location: drivers/md/md.c:8238
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
```
**Symbols:**

```
ffffffff81727950-ffffffff81727d40: remove_and_add_spares (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int remove_and_add_spares(struct mddev *mddev, struct md_rdev *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817401d0)
Location: drivers/md/md.c:8489
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
```
**Symbols:**

```
ffffffff817401d0-ffffffff81740580: remove_and_add_spares (STB_LOCAL)
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
In drivers/md/md.c (ffffffff817b88b0)
Location: drivers/md/md.c:8549
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
```
**Symbols:**

```
ffffffff817b1dd0-ffffffff817b218c: remove_and_add_spares.part.55 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int remove_and_add_spares(struct mddev *mddev, struct md_rdev *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817f5e20)
Location: drivers/md/md.c:8635
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
```
**Symbols:**

```
ffffffff817f5e20-ffffffff817f61ff: remove_and_add_spares (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int remove_and_add_spares(struct mddev *mddev, struct md_rdev *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81821da0)
Location: drivers/md/md.c:8648
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
```
**Symbols:**

```
ffffffff81821da0-ffffffff81822173: remove_and_add_spares (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int remove_and_add_spares(struct mddev *mddev, struct md_rdev *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81863e00)
Location: drivers/md/md.c:8717
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
```
**Symbols:**

```
ffffffff81863e00-ffffffff818641da: remove_and_add_spares (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int remove_and_add_spares(struct mddev *mddev, struct md_rdev *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81895b40)
Location: drivers/md/md.c:8821
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
```
**Symbols:**

```
ffffffff81895b40-ffffffff81895f1a: remove_and_add_spares (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int remove_and_add_spares(struct mddev *mddev, struct md_rdev *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81967180)
Location: drivers/md/md.c:9018
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
```
**Symbols:**

```
ffffffff81967180-ffffffff81967569: remove_and_add_spares (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int remove_and_add_spares(struct mddev *mddev, struct md_rdev *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8196dd10)
Location: drivers/md/md.c:9049
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
```
**Symbols:**

```
ffffffff8196dd10-ffffffff8196e0f8: remove_and_add_spares (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int remove_and_add_spares(struct mddev *mddev, struct md_rdev *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff819522e0)
Location: drivers/md/md.c:9027
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
```
**Symbols:**

```
ffffffff819522e0-ffffffff819526c8: remove_and_add_spares (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int remove_and_add_spares(struct mddev *mddev, struct md_rdev *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff819f7850)
Location: drivers/md/md.c:9092
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
```
**Symbols:**

```
ffffffff819f7850-ffffffff819f7c38: remove_and_add_spares (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int remove_and_add_spares(struct mddev *mddev, struct md_rdev *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81b600e0)
Location: drivers/md/md.c:9095
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
```
**Symbols:**

```
ffffffff81b600e0-ffffffff81b60511: remove_and_add_spares (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int remove_and_add_spares(struct mddev *mddev, struct md_rdev *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81cf8f30)
Location: drivers/md/md.c:9106
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
```
**Symbols:**

```
ffffffff81cf8f30-ffffffff81cf9372: remove_and_add_spares (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int remove_and_add_spares(struct mddev *mddev, struct md_rdev *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d60c40)
Location: drivers/md/md.c:9122
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
```
**Symbols:**

```
ffffffff81d60c40-ffffffff81d61082: remove_and_add_spares (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int remove_and_add_spares(struct mddev *mddev, struct md_rdev *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e17950)
Location: drivers/md/md.c:9279
Inline: False
Direct callers:
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_choose_sync_action
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
```
**Symbols:**

```
ffffffff81e17950-ffffffff81e17c7b: remove_and_add_spares (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int remove_and_add_spares(struct mddev *mddev, struct md_rdev *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010ae7068)
Location: drivers/md/md.c:8821
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
```
**Symbols:**

```
ffff800010ae7068-ffff800010ae73f8: remove_and_add_spares (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int remove_and_add_spares(struct mddev *mddev, struct md_rdev *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bccfc8)
Location: drivers/md/md.c:8821
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
```
**Symbols:**

```
c0bccfc8-c0bcd3c0: remove_and_add_spares (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int remove_and_add_spares(struct mddev *mddev, struct md_rdev *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bd7550)
Location: drivers/md/md.c:8821
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
```
**Symbols:**

```
c000000000bd7550-c000000000bd7a70: remove_and_add_spares (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int remove_and_add_spares(struct mddev *mddev, struct md_rdev *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006de442)
Location: drivers/md/md.c:8821
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
```
**Symbols:**

```
ffffffe0006de442-ffffffe0006de70e: remove_and_add_spares (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int remove_and_add_spares(struct mddev *mddev, struct md_rdev *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8183b9c0)
Location: drivers/md/md.c:8821
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
```
**Symbols:**

```
ffffffff8183b9c0-ffffffff8183bd9a: remove_and_add_spares (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int remove_and_add_spares(struct mddev *mddev, struct md_rdev *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81803020)
Location: drivers/md/md.c:8821
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
```
**Symbols:**

```
ffffffff81803020-ffffffff818033fa: remove_and_add_spares (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int remove_and_add_spares(struct mddev *mddev, struct md_rdev *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8188aff0)
Location: drivers/md/md.c:8821
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
```
**Symbols:**

```
ffffffff8188aff0-ffffffff8188b3ca: remove_and_add_spares (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int remove_and_add_spares(struct mddev *mddev, struct md_rdev *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818aa260)
Location: drivers/md/md.c:8821
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
```
**Symbols:**

```
ffffffff818aa260-ffffffff818aa63a: remove_and_add_spares (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
