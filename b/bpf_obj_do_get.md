# Function: <code>bpf_obj_do_get</code>

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
In kernel/bpf/inode.c (ffffffff81177181)
Location: kernel/bpf/inode.c:258
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
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
In kernel/bpf/inode.c (ffffffff81185c26)
Location: kernel/bpf/inode.c:257
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
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
In kernel/bpf/inode.c (ffffffff81192ff6)
Location: kernel/bpf/inode.c:289
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
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
In kernel/bpf/inode.c (ffffffff81199f65)
Location: kernel/bpf/inode.c:297
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
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
In kernel/bpf/inode.c (ffffffff811a9306)
Location: kernel/bpf/inode.c:297
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
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
In kernel/bpf/inode.c (ffffffff811c08c6)
Location: kernel/bpf/inode.c:449
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
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
In kernel/bpf/inode.c (ffffffff811d1d26)
Location: kernel/bpf/inode.c:450
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
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
In kernel/bpf/inode.c (ffffffff811e603b)
Location: kernel/bpf/inode.c:447
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
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
In kernel/bpf/inode.c (ffffffff811f278b)
Location: kernel/bpf/inode.c:447
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *bpf_obj_do_get(const char *pathname, enum bpf_type *type, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81213be0)
Location: kernel/bpf/inode.c:474
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff81213be0-ffffffff81213d07: bpf_obj_do_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *bpf_obj_do_get(const char *pathname, enum bpf_type *type, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81215480)
Location: kernel/bpf/inode.c:497
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff81215480-ffffffff812155a7: bpf_obj_do_get (STB_LOCAL)
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
In kernel/bpf/inode.c (ffffffff81218d42)
Location: kernel/bpf/inode.c:498
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
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
In kernel/bpf/inode.c (ffffffff8124f452)
Location: kernel/bpf/inode.c:498
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
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
In kernel/bpf/inode.c (ffffffff81296591)
Location: kernel/bpf/inode.c:498
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
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
In kernel/bpf/inode.c (ffffffff812f14a1)
Location: kernel/bpf/inode.c:498
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
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
In kernel/bpf/inode.c (ffffffff8131e0a4)
Location: kernel/bpf/inode.c:497
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
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
In kernel/bpf/inode.c (ffffffff813404c4)
Location: kernel/bpf/inode.c:494
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
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
In kernel/bpf/inode.c (ffff80001027607c)
Location: kernel/bpf/inode.c:447
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
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
In kernel/bpf/inode.c (c04a86e4)
Location: kernel/bpf/inode.c:447
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
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
In kernel/bpf/inode.c (c00000000031e450)
Location: kernel/bpf/inode.c:447
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
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
In kernel/bpf/inode.c (ffffffe0001ae5d8)
Location: kernel/bpf/inode.c:447
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
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
In kernel/bpf/inode.c (ffffffff811eadab)
Location: kernel/bpf/inode.c:447
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
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
In kernel/bpf/inode.c (ffffffff811ddb6b)
Location: kernel/bpf/inode.c:447
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
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
In kernel/bpf/inode.c (ffffffff811e8b7b)
Location: kernel/bpf/inode.c:447
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
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
In kernel/bpf/inode.c (ffffffff811f6f2b)
Location: kernel/bpf/inode.c:447
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
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
