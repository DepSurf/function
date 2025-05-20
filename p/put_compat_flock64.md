# Function: <code>put_compat_flock64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int put_compat_flock64(struct flock *kfl, struct compat_flock64 *ufl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff81263270)
Location: fs/compat.c:389
Inline: False
```
**Symbols:**

```
ffffffff81263270-ffffffff812632f7: put_compat_flock64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int put_compat_flock64(struct flock *kfl, struct compat_flock64 *ufl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff8128f4c0)
Location: fs/compat.c:389
Inline: False
```
**Symbols:**

```
ffffffff8128f4c0-ffffffff8128f543: put_compat_flock64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int put_compat_flock64(struct flock *kfl, struct compat_flock64 *ufl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff812a44b0)
Location: fs/compat.c:375
Inline: False
```
**Symbols:**

```
ffffffff812a44b0-ffffffff812a4533: put_compat_flock64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int put_compat_flock64(const struct flock *kfl, struct compat_flock64 *ufl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81265750)
Location: fs/fcntl.c:564
Inline: False
Direct callers:
  - fs/fcntl.c:compat_SyS_fcntl
```
**Symbols:**

```
ffffffff81265750-ffffffff812657c6: put_compat_flock64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int put_compat_flock64(const struct flock *kfl, struct compat_flock64 *ufl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81287ea0)
Location: fs/fcntl.c:565
Inline: False
Direct callers:
  - fs/fcntl.c:compat_SyS_fcntl
```
**Symbols:**

```
ffffffff81287ea0-ffffffff81287f16: put_compat_flock64 (STB_LOCAL)
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
In fs/fcntl.c (ffffffff812af029)
Location: fs/fcntl.c:565
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff812c4106)
Location: fs/fcntl.c:565
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff812e0b7a)
Location: fs/fcntl.c:565
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff812f262a)
Location: fs/fcntl.c:565
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff8132a894)
Location: fs/fcntl.c:565
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff81335e04)
Location: fs/fcntl.c:565
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff8133bf76)
Location: fs/fcntl.c:570
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff81389bf6)
Location: fs/fcntl.c:574
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff8140ace7)
Location: fs/fcntl.c:552
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff81495557)
Location: fs/fcntl.c:553
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff814ca580)
Location: fs/fcntl.c:554
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff814fce50)
Location: fs/fcntl.c:555
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffff80001039c890)
Location: fs/fcntl.c:565
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (c0000000004976b0)
Location: fs/fcntl.c:565
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In fs/fcntl.c (ffffffff812eac0a)
Location: fs/fcntl.c:565
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff812db84a)
Location: fs/fcntl.c:565
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff812e8a1a)
Location: fs/fcntl.c:565
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff812f99ea)
Location: fs/fcntl.c:565
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct flock *kfl</code> ➡️ <code>const struct flock *kfl</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
