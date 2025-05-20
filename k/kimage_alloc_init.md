# Function: <code>kimage_alloc_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kimage_alloc_init(struct kimage **rimage, long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (ffffffff8110dd80)
Location: kernel/kexec.c:41
Inline: False
Direct callers:
  - kernel/kexec.c:compat_SyS_kexec_load
  - kernel/kexec.c:compat_SyS_kexec_load
```
**Symbols:**

```
ffffffff8110dd80-ffffffff8110dee7: kimage_alloc_init (STB_LOCAL)
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
In kernel/kexec.c (ffffffff81115754)
Location: kernel/kexec.c:41
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
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
In kernel/kexec.c (ffffffff8111ce74)
Location: kernel/kexec.c:41
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
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
In kernel/kexec.c (ffffffff8111ea8f)
Location: kernel/kexec.c:40
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
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
In kernel/kexec.c (ffffffff8112a1ef)
Location: kernel/kexec.c:40
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
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
In kernel/kexec.c (ffffffff81138148)
Location: kernel/kexec.c:40
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
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
In kernel/kexec.c (ffffffff81143968)
Location: kernel/kexec.c:41
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
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
In kernel/kexec.c (ffffffff8114ecc4)
Location: kernel/kexec.c:39
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
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
In kernel/kexec.c (ffffffff8115a9d4)
Location: kernel/kexec.c:39
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int kimage_alloc_init(struct kimage **rimage, long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec.c (0)
Location: kernel/kexec.c:39
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
```
**Symbols:**

```
ffffffff8116b770-ffffffff8116b8b2: kimage_alloc_init (STB_LOCAL)
ffffffff8116bf80-ffffffff8116bfba: kimage_alloc_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int kimage_alloc_init(struct kimage **rimage, long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec.c (0)
Location: kernel/kexec.c:39
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
```
**Symbols:**

```
ffffffff81167e70-ffffffff81167fb0: kimage_alloc_init (STB_LOCAL)
ffffffff81be45ba-ffffffff81be45f4: kimage_alloc_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int kimage_alloc_init(struct kimage **rimage, long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec.c (0)
Location: kernel/kexec.c:39
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
```
**Symbols:**

```
ffffffff81168c10-ffffffff81168d50: kimage_alloc_init (STB_LOCAL)
ffffffff81bd63db-ffffffff81bd6415: kimage_alloc_init.cold (STB_LOCAL)
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
In kernel/kexec.c (ffffffff8118e9bf)
Location: kernel/kexec.c:22
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int kimage_alloc_init(struct kimage **rimage, long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec.c (0)
Location: kernel/kexec.c:22
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
```
**Symbols:**

```
ffffffff811bdfe0-ffffffff811be11e: kimage_alloc_init (STB_LOCAL)
ffffffff81e63ac0-ffffffff81e63af1: kimage_alloc_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int kimage_alloc_init(struct kimage **rimage, long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec.c (0)
Location: kernel/kexec.c:22
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
```
**Symbols:**

```
ffffffff81200040-ffffffff812001ef: kimage_alloc_init (STB_LOCAL)
ffffffff8205c054-ffffffff8205c077: kimage_alloc_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int kimage_alloc_init(struct kimage **rimage, long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec.c (0)
Location: kernel/kexec.c:22
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
```
**Symbols:**

```
ffffffff812154a0-ffffffff8121564f: kimage_alloc_init (STB_LOCAL)
ffffffff820da84b-ffffffff820da86e: kimage_alloc_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int kimage_alloc_init(struct kimage **rimage, long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec.c (0)
Location: kernel/kexec.c:22
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
```
**Symbols:**

```
ffffffff8122d440-ffffffff8122d5ef: kimage_alloc_init (STB_LOCAL)
ffffffff821b63f6-ffffffff821b6419: kimage_alloc_init.cold (STB_LOCAL)
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
In kernel/kexec.c (ffff8000101ca0a4)
Location: kernel/kexec.c:39
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
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
In kernel/kexec.c (c0410e94)
Location: kernel/kexec.c:39
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
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
In kernel/kexec.c (c000000000232a98)
Location: kernel/kexec.c:39
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
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
In kernel/kexec.c (ffffffff81152ff4)
Location: kernel/kexec.c:39
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
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
In kernel/kexec.c (ffffffff81146314)
Location: kernel/kexec.c:39
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
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
In kernel/kexec.c (ffffffff81150ea4)
Location: kernel/kexec.c:39
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
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
In kernel/kexec.c (ffffffff8115dcc4)
Location: kernel/kexec.c:39
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
