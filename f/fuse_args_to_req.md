# Function: <code>fuse_args_to_req</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814221a6)
Location: fs/fuse/dev.c:467
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
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
In fs/fuse/dev.c (ffffffff8146e859)
Location: fs/fuse/dev.c:467
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
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
In fs/fuse/dev.c (ffffffff81488fe1)
Location: fs/fuse/dev.c:478
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
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
In fs/fuse/dev.c (ffffffff8148e8e7)
Location: fs/fuse/dev.c:478
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
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
In fs/fuse/dev.c (ffffffff814e6357)
Location: fs/fuse/dev.c:478
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
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
In fs/fuse/dev.c (ffffffff81574ede)
Location: fs/fuse/dev.c:474
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
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
In fs/fuse/dev.c (ffffffff8161a9e1)
Location: fs/fuse/dev.c:474
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fuse_args_to_req(struct fuse_req *req, struct fuse_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff816514d0)
Location: fs/fuse/dev.c:474
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
```
**Symbols:**

```
ffffffff816514d0-ffffffff81651548: fuse_args_to_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fuse_args_to_req(struct fuse_req *req, struct fuse_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8168aae0)
Location: fs/fuse/dev.c:474
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
```
**Symbols:**

```
ffffffff8168aae0-ffffffff8168ab58: fuse_args_to_req (STB_LOCAL)
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
In fs/fuse/dev.c (ffff800010504e80)
Location: fs/fuse/dev.c:467
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
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
In fs/fuse/dev.c (c06bf76c)
Location: fs/fuse/dev.c:467
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_retrieve
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
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
In fs/fuse/dev.c (c00000000064a100)
Location: fs/fuse/dev.c:467
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
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
In fs/fuse/dev.c (ffffffe000371964)
Location: fs/fuse/dev.c:467
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
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
In fs/fuse/dev.c (ffffffff8141a786)
Location: fs/fuse/dev.c:467
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
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
In fs/fuse/dev.c (ffffffff8140b206)
Location: fs/fuse/dev.c:467
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
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
In fs/fuse/dev.c (ffffffff81416926)
Location: fs/fuse/dev.c:467
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
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
In fs/fuse/dev.c (ffffffff8142d686)
Location: fs/fuse/dev.c:467
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
