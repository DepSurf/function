# Function: <code>md_set_readonly</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int md_set_readonly(struct mddev *mddev, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81696f80)
Location: drivers/md/md.c:5534
Inline: False
Direct callers:
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81696f80-ffffffff81697235: md_set_readonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int md_set_readonly(struct mddev *mddev, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff816f7f40)
Location: drivers/md/md.c:5547
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff816f7f40-ffffffff816f81f9: md_set_readonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int md_set_readonly(struct mddev *mddev, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81728fc0)
Location: drivers/md/md.c:5600
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff81728fc0-ffffffff8172925c: md_set_readonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int md_set_readonly(struct mddev *mddev, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81741760)
Location: drivers/md/md.c:5815
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff81741760-ffffffff81741a02: md_set_readonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int md_set_readonly(struct mddev *mddev, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817b3880)
Location: drivers/md/md.c:5866
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff817b3880-ffffffff817b3b22: md_set_readonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int md_set_readonly(struct mddev *mddev, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5932
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff817fb300-ffffffff817fb553: md_set_readonly (STB_LOCAL)
ffffffff81800b46-ffffffff81800b9d: md_set_readonly.cold.87 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int md_set_readonly(struct mddev *mddev, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5919
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff818273f0-ffffffff81827643: md_set_readonly (STB_LOCAL)
ffffffff8182cd49-ffffffff8182cda0: md_set_readonly.cold.86 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int md_set_readonly(struct mddev *mddev, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5981
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff818698c0-ffffffff81869b10: md_set_readonly (STB_LOCAL)
ffffffff8186f2ff-ffffffff8186f358: md_set_readonly.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int md_set_readonly(struct mddev *mddev, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6082
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff8189b670-ffffffff8189b8c0: md_set_readonly (STB_LOCAL)
ffffffff818a10c2-ffffffff818a111b: md_set_readonly.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int md_set_readonly(struct mddev *mddev, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6280
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff8196ac40-ffffffff8196ae97: md_set_readonly (STB_LOCAL)
ffffffff81970da2-ffffffff81970e0c: md_set_readonly.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int md_set_readonly(struct mddev *mddev, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6314
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff819717c0-ffffffff81971a17: md_set_readonly (STB_LOCAL)
ffffffff81c26e8b-ffffffff81c26ef5: md_set_readonly.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int md_set_readonly(struct mddev *mddev, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6271
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff819558b0-ffffffff81955b07: md_set_readonly (STB_LOCAL)
ffffffff81c1903c-ffffffff81c190a6: md_set_readonly.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int md_set_readonly(struct mddev *mddev, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6284
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff819faee0-ffffffff819fb137: md_set_readonly (STB_LOCAL)
ffffffff81d28658-ffffffff81d286c2: md_set_readonly.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int md_set_readonly(struct mddev *mddev, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6277
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff81b623d0-ffffffff81b62695: md_set_readonly (STB_LOCAL)
ffffffff81ef46e1-ffffffff81ef472f: md_set_readonly.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int md_set_readonly(struct mddev *mddev, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81cfc600)
Location: drivers/md/md.c:6264
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff81cfc600-ffffffff81cfc914: md_set_readonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int md_set_readonly(struct mddev *mddev, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d672e0)
Location: drivers/md/md.c:6264
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff81d672e0-ffffffff81d67606: md_set_readonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int md_set_readonly(struct mddev *mddev, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e1e260)
Location: drivers/md/md.c:6394
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff81e1e260-ffffffff81e1e4bb: md_set_readonly (STB_LOCAL)
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
int md_set_readonly(struct mddev *mddev, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010aefb30)
Location: drivers/md/md.c:6082
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffff800010aefb30-ffff800010aefdc0: md_set_readonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int md_set_readonly(struct mddev *mddev, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bd0fe0)
Location: drivers/md/md.c:6082
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
c0bd0fe0-c0bd1288: md_set_readonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int md_set_readonly(struct mddev *mddev, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bdb5e0)
Location: drivers/md/md.c:6082
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
c000000000bdb5e0-c000000000bdb964: md_set_readonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int md_set_readonly(struct mddev *mddev, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006e3eae)
Location: drivers/md/md.c:6082
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffe0006e3eae-ffffffe0006e40e4: md_set_readonly (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int md_set_readonly(struct mddev *mddev, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6082
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff818414f0-ffffffff81841740: md_set_readonly (STB_LOCAL)
ffffffff81846f42-ffffffff81846f9b: md_set_readonly.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int md_set_readonly(struct mddev *mddev, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6082
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff81808b50-ffffffff81808da0: md_set_readonly (STB_LOCAL)
ffffffff8180e5a2-ffffffff8180e5fb: md_set_readonly.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int md_set_readonly(struct mddev *mddev, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6082
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff81890b20-ffffffff81890d70: md_set_readonly (STB_LOCAL)
ffffffff81896572-ffffffff818965cb: md_set_readonly.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int md_set_readonly(struct mddev *mddev, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6082
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff818ac710-ffffffff818ac956: md_set_readonly (STB_LOCAL)
ffffffff818b2552-ffffffff818b25ab: md_set_readonly.cold (STB_LOCAL)
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
