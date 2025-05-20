# Function: <code>shrink_submounts</code>

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
In fs/namespace.c (ffffffff8122d45d)
Location: fs/namespace.c:2565
Inline: True
Inline callers:
  - fs/namespace.c:do_umount
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
In fs/namespace.c (ffffffff81255c02)
Location: fs/namespace.c:2551
Inline: True
Inline callers:
  - fs/namespace.c:do_umount
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
In fs/namespace.c (ffffffff81268ff2)
Location: fs/namespace.c:2670
Inline: True
Inline callers:
  - fs/namespace.c:do_umount
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
In fs/namespace.c (ffffffff812767a6)
Location: fs/namespace.c:2612
Inline: True
Inline callers:
  - fs/namespace.c:do_umount
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
In fs/namespace.c (ffffffff812990f9)
Location: fs/namespace.c:2677
Inline: True
Inline callers:
  - fs/namespace.c:do_umount
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
In fs/namespace.c (ffffffff812bfd63)
Location: fs/namespace.c:2708
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
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
In fs/namespace.c (ffffffff812d4f81)
Location: fs/namespace.c:2678
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
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
In fs/namespace.c (ffffffff812f2439)
Location: fs/namespace.c:2944
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
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
In fs/namespace.c (ffffffff81303ff6)
Location: fs/namespace.c:2975
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void shrink_submounts(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133b610)
Location: fs/namespace.c:3068
Inline: False
Direct callers:
  - fs/namespace.c:do_umount
```
**Symbols:**

```
ffffffff8133b610-ffffffff8133b753: shrink_submounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void shrink_submounts(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813474b0)
Location: fs/namespace.c:3074
Inline: False
Direct callers:
  - fs/namespace.c:do_umount
```
**Symbols:**

```
ffffffff813474b0-ffffffff813475f3: shrink_submounts (STB_LOCAL)
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
In fs/namespace.c (ffffffff8134f7e3)
Location: fs/namespace.c:3107
Inline: True
Inline callers:
  - fs/namespace.c:do_umount
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
In fs/namespace.c (ffffffff8139dad5)
Location: fs/namespace.c:3181
Inline: True
Inline callers:
  - fs/namespace.c:do_umount
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
In fs/namespace.c (ffffffff81420ab6)
Location: fs/namespace.c:3224
Inline: True
Inline callers:
  - fs/namespace.c:do_umount
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
In fs/namespace.c (ffffffff814ad1b4)
Location: fs/namespace.c:3329
Inline: True
Inline callers:
  - fs/namespace.c:do_umount
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
In fs/namespace.c (ffffffff814e1f95)
Location: fs/namespace.c:3516
Inline: True
Inline callers:
  - fs/namespace.c:do_umount
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
In fs/namespace.c (ffffffff8151606f)
Location: fs/namespace.c:3533
Inline: True
Inline callers:
  - fs/namespace.c:do_umount
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
In fs/namespace.c (ffff8000103b77f8)
Location: fs/namespace.c:2975
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
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
In fs/namespace.c (c0594e14)
Location: fs/namespace.c:2975
Inline: True
Inline callers:
  - fs/namespace.c:do_umount
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
In fs/namespace.c (c0000000004b43d8)
Location: fs/namespace.c:2975
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
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
In fs/namespace.c (ffffffe00027a302)
Location: fs/namespace.c:2975
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
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
In fs/namespace.c (ffffffff812fc5d6)
Location: fs/namespace.c:2975
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
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
In fs/namespace.c (ffffffff812ed1f6)
Location: fs/namespace.c:2975
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
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
In fs/namespace.c (ffffffff812fa3c6)
Location: fs/namespace.c:2975
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
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
In fs/namespace.c (ffffffff8130b702)
Location: fs/namespace.c:2975
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
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
