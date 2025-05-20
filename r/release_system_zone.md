# Function: <code>release_system_zone</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void release_system_zone(struct ext4_system_blocks *system_blks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff8138f220)
Location: fs/ext4/block_validity.c:53
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_destroy_system_zone
```
**Symbols:**

```
ffffffff8138f220-ffffffff8138f267: release_system_zone (STB_LOCAL)
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
In fs/ext4/block_validity.c (ffffffff813da9c9)
Location: fs/ext4/block_validity.c:55
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_destroy_system_zone
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
In fs/ext4/block_validity.c (ffffffff813ec6a2)
Location: fs/ext4/block_validity.c:55
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_destroy_system_zone
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
In fs/ext4/block_validity.c (ffffffff813f2be2)
Location: fs/ext4/block_validity.c:55
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_destroy_system_zone
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
In fs/ext4/block_validity.c (ffffffff81444bcb)
Location: fs/ext4/block_validity.c:55
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_destroy_system_zone
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
In fs/ext4/block_validity.c (ffffffff814c0b6e)
Location: fs/ext4/block_validity.c:55
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_destroy_system_zone
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
In fs/ext4/block_validity.c (ffffffff81558c4e)
Location: fs/ext4/block_validity.c:55
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_destroy_system_zone
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
In fs/ext4/block_validity.c (ffffffff81590a9e)
Location: fs/ext4/block_validity.c:55
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_destroy_system_zone
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
In fs/ext4/block_validity.c (ffffffff815c97d9)
Location: fs/ext4/block_validity.c:55
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_destroy_system_zone
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
void release_system_zone(struct ext4_system_blocks *system_blks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffff800010461a38)
Location: fs/ext4/block_validity.c:53
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_destroy_system_zone
```
**Symbols:**

```
ffff800010461a38-ffff800010461ab0: release_system_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void release_system_zone(struct ext4_system_blocks *system_blks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (c0622020)
Location: fs/ext4/block_validity.c:53
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_destroy_system_zone
```
**Symbols:**

```
c0622020-c0622074: release_system_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void release_system_zone(struct ext4_system_blocks *system_blks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (c00000000057e240)
Location: fs/ext4/block_validity.c:53
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_destroy_system_zone
```
**Symbols:**

```
c00000000057e240-c00000000057e2d8: release_system_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void release_system_zone(struct ext4_system_blocks *system_blks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffe0002f0a4e)
Location: fs/ext4/block_validity.c:53
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_destroy_system_zone
```
**Symbols:**

```
ffffffe0002f0a4e-ffffffe0002f0ac2: release_system_zone (STB_LOCAL)
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
void release_system_zone(struct ext4_system_blocks *system_blks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff81387800)
Location: fs/ext4/block_validity.c:53
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_destroy_system_zone
```
**Symbols:**

```
ffffffff81387800-ffffffff81387847: release_system_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void release_system_zone(struct ext4_system_blocks *system_blks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff81378290)
Location: fs/ext4/block_validity.c:53
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_destroy_system_zone
```
**Symbols:**

```
ffffffff81378290-ffffffff813782d7: release_system_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void release_system_zone(struct ext4_system_blocks *system_blks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff813852d0)
Location: fs/ext4/block_validity.c:53
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_destroy_system_zone
```
**Symbols:**

```
ffffffff813852d0-ffffffff81385317: release_system_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void release_system_zone(struct ext4_system_blocks *system_blks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff81398e50)
Location: fs/ext4/block_validity.c:53
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_destroy_system_zone
```
**Symbols:**

```
ffffffff81398e50-ffffffff81398e97: release_system_zone (STB_LOCAL)
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
