# Function: <code>leak_balloon</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int leak_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff814c3a40)
Location: drivers/virtio/virtio_balloon.c:185
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_oom_notify
  - drivers/virtio/virtio_balloon.c:balloon
```
**Symbols:**

```
ffffffff814c3a40-ffffffff814c3b8f: leak_balloon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int leak_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81514400)
Location: drivers/virtio/virtio_balloon.c:200
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_oom_notify
```
**Symbols:**

```
ffffffff81514400-ffffffff81514592: leak_balloon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int leak_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff815404b0)
Location: drivers/virtio/virtio_balloon.c:200
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_oom_notify
```
**Symbols:**

```
ffffffff815404b0-ffffffff8154063b: leak_balloon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int leak_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff815548a0)
Location: drivers/virtio/virtio_balloon.c:195
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_oom_notify
```
**Symbols:**

```
ffffffff815548a0-ffffffff81554a88: leak_balloon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int leak_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff815b8410)
Location: drivers/virtio/virtio_balloon.c:208
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_oom_notify
```
**Symbols:**

```
ffffffff815b8410-ffffffff815b8629: leak_balloon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int leak_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff815f09e0)
Location: drivers/virtio/virtio_balloon.c:208
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_oom_notify
```
**Symbols:**

```
ffffffff815f09e0-ffffffff815f0bfa: leak_balloon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int leak_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff8160b0b0)
Location: drivers/virtio/virtio_balloon.c:245
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
```
**Symbols:**

```
ffffffff8160b0b0-ffffffff8160b2ca: leak_balloon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int leak_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff8163eeb0)
Location: drivers/virtio/virtio_balloon.c:233
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
```
**Symbols:**

```
ffffffff8163eeb0-ffffffff8163f0c9: leak_balloon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int leak_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81661440)
Location: drivers/virtio/virtio_balloon.c:235
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
```
**Symbols:**

```
ffffffff81661440-ffffffff81661659: leak_balloon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int leak_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff817101d0)
Location: drivers/virtio/virtio_balloon.c:275
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_oom_notify
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
```
**Symbols:**

```
ffffffff817101d0-ffffffff817103e9: leak_balloon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int leak_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff8172cec0)
Location: drivers/virtio/virtio_balloon.c:275
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_oom_notify
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
```
**Symbols:**

```
ffffffff8172cec0-ffffffff8172d0d3: leak_balloon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int leak_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81710ca0)
Location: drivers/virtio/virtio_balloon.c:275
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_oom_notify
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
```
**Symbols:**

```
ffffffff81710ca0-ffffffff81710eaf: leak_balloon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int leak_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff8178d7a0)
Location: drivers/virtio/virtio_balloon.c:275
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_oom_notify
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
```
**Symbols:**

```
ffffffff8178d7a0-ffffffff8178d9ac: leak_balloon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int leak_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff818c5860)
Location: drivers/virtio/virtio_balloon.c:275
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_oom_notify
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
```
**Symbols:**

```
ffffffff818c5860-ffffffff818c5aa9: leak_balloon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int leak_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81a162e0)
Location: drivers/virtio/virtio_balloon.c:268
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_oom_notify
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
```
**Symbols:**

```
ffffffff81a162e0-ffffffff81a16529: leak_balloon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int leak_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81a5f390)
Location: drivers/virtio/virtio_balloon.c:268
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_oom_notify
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
```
**Symbols:**

```
ffffffff81a5f390-ffffffff81a5f5ce: leak_balloon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int leak_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81ab19c0)
Location: drivers/virtio/virtio_balloon.c:273
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_oom_notify
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
```
**Symbols:**

```
ffffffff81ab19c0-ffffffff81ab1bfb: leak_balloon (STB_LOCAL)
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
unsigned int leak_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffff800010829c88)
Location: drivers/virtio/virtio_balloon.c:235
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
```
**Symbols:**

```
ffff800010829c88-ffff800010829e7c: leak_balloon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int leak_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (c0948318)
Location: drivers/virtio/virtio_balloon.c:235
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
```
**Symbols:**

```
c0948318-c0948544: leak_balloon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int leak_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (c0000000008d69c0)
Location: drivers/virtio/virtio_balloon.c:235
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
```
**Symbols:**

```
c0000000008d69c0-c0000000008d6cb4: leak_balloon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int leak_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffe00051fe1e)
Location: drivers/virtio/virtio_balloon.c:235
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
```
**Symbols:**

```
ffffffe00051fe1e-ffffffe00051ffc4: leak_balloon (STB_LOCAL)
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
unsigned int leak_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff816272b0)
Location: drivers/virtio/virtio_balloon.c:235
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
```
**Symbols:**

```
ffffffff816272b0-ffffffff816274c9: leak_balloon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int leak_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff8161b930)
Location: drivers/virtio/virtio_balloon.c:235
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
```
**Symbols:**

```
ffffffff8161b930-ffffffff8161bb49: leak_balloon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int leak_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81655280)
Location: drivers/virtio/virtio_balloon.c:235
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
```
**Symbols:**

```
ffffffff81655280-ffffffff81655499: leak_balloon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int leak_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff8166fc20)
Location: drivers/virtio/virtio_balloon.c:235
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
```
**Symbols:**

```
ffffffff8166fc20-ffffffff8166fe39: leak_balloon (STB_LOCAL)
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
