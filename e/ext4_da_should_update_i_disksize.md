# Function: <code>ext4_da_should_update_i_disksize</code>

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
In fs/ext4/inode.c (ffffffff8129e149)
Location: fs/ext4/inode.c:2784
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
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
In fs/ext4/inode.c (ffffffff812cc627)
Location: fs/ext4/inode.c:2973
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
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
In fs/ext4/inode.c (ffffffff812e2437)
Location: fs/ext4/inode.c:3000
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
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
In fs/ext4/inode.c (ffffffff813065b0)
Location: fs/ext4/inode.c:3116
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
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
In fs/ext4/inode.c (ffffffff8132b180)
Location: fs/ext4/inode.c:3109
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
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
In fs/ext4/inode.c (ffffffff8135982a)
Location: fs/ext4/inode.c:3110
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
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
In fs/ext4/inode.c (ffffffff81371b5f)
Location: fs/ext4/inode.c:3141
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
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
In fs/ext4/inode.c (ffffffff8139b0e5)
Location: fs/ext4/inode.c:3154
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
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
In fs/ext4/inode.c (ffffffff813b3ba5)
Location: fs/ext4/inode.c:3135
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
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
In fs/ext4/inode.c (ffffffff813fee4c)
Location: fs/ext4/inode.c:3028
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_da_should_update_i_disksize(struct page *page, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81408090)
Location: fs/ext4/inode.c:3048
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
**Symbols:**

```
ffffffff81408090-ffffffff814080ef: ext4_da_should_update_i_disksize (STB_LOCAL)
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
In fs/ext4/inode.c (ffffffff814179fc)
Location: fs/ext4/inode.c:3047
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
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
In fs/ext4/inode.c (ffffffff8146acd5)
Location: fs/ext4/inode.c:2980
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
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
In fs/ext4/inode.c (ffffffff814ead6b)
Location: fs/ext4/inode.c:3024
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
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
In fs/ext4/inode.c (ffffffff815848c8)
Location: fs/ext4/inode.c:3112
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
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
In fs/ext4/inode.c (ffffffff815bb285)
Location: fs/ext4/inode.c:2921
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
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
In fs/ext4/inode.c (ffffffff815f3fd1)
Location: fs/ext4/inode.c:2923
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
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
In fs/ext4/inode.c (ffff800010488434)
Location: fs/ext4/inode.c:3135
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
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
In fs/ext4/inode.c (c064a600)
Location: fs/ext4/inode.c:3135
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
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
In fs/ext4/inode.c (c0000000005aed10)
Location: fs/ext4/inode.c:3135
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
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
In fs/ext4/inode.c (ffffffe00030fe92)
Location: fs/ext4/inode.c:3135
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
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
In fs/ext4/inode.c (ffffffff813ac185)
Location: fs/ext4/inode.c:3135
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
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
In fs/ext4/inode.c (ffffffff8139cc15)
Location: fs/ext4/inode.c:3135
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
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
In fs/ext4/inode.c (ffffffff813a99e5)
Location: fs/ext4/inode.c:3135
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
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
In fs/ext4/inode.c (ffffffff813be2ee)
Location: fs/ext4/inode.c:3135
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
