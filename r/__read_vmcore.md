# Function: <code>__read_vmcore</code>

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
In fs/proc/vmcore.c (ffffffff812876a5)
Location: fs/proc/vmcore.c:184
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
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
In fs/proc/vmcore.c (ffffffff812b49c1)
Location: fs/proc/vmcore.c:184
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
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
In fs/proc/vmcore.c (ffffffff812ca251)
Location: fs/proc/vmcore.c:184
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
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
In fs/proc/vmcore.c (ffffffff812d7721)
Location: fs/proc/vmcore.c:184
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
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
In fs/proc/vmcore.c (ffffffff812fbe01)
Location: fs/proc/vmcore.c:184
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
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
In fs/proc/vmcore.c (ffffffff81329738)
Location: fs/proc/vmcore.c:269
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
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
In fs/proc/vmcore.c (ffffffff81340f78)
Location: fs/proc/vmcore.c:290
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
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
In fs/proc/vmcore.c (ffffffff81369358)
Location: fs/proc/vmcore.c:295
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
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
In fs/proc/vmcore.c (ffffffff813815a8)
Location: fs/proc/vmcore.c:295
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff813cbb10)
Location: fs/proc/vmcore.c:295
Inline: True
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffffffff813cbb10-ffffffff813cbdf6: __read_vmcore.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff813dd7a0)
Location: fs/proc/vmcore.c:295
Inline: True
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffffffff813dd7a0-ffffffff813dda86: __read_vmcore.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff813e4680)
Location: fs/proc/vmcore.c:295
Inline: True
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffffffff813e4680-ffffffff813e4966: __read_vmcore.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81436250)
Location: fs/proc/vmcore.c:299
Inline: True
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffffffff81436250-ffffffff81436536: __read_vmcore.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t __read_vmcore(struct iov_iter *iter, loff_t *fpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff814b08c0)
Location: fs/proc/vmcore.c:318
Inline: False
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffffffff814b08c0-ffffffff814b0c38: __read_vmcore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t __read_vmcore(struct iov_iter *iter, loff_t *fpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff815471c0)
Location: fs/proc/vmcore.c:317
Inline: False
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffffffff815471c0-ffffffff81547538: __read_vmcore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t __read_vmcore(struct iov_iter *iter, loff_t *fpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff8157ede0)
Location: fs/proc/vmcore.c:317
Inline: False
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffffffff8157ede0-ffffffff8157f158: __read_vmcore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t __read_vmcore(struct iov_iter *iter, loff_t *fpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff815b7820)
Location: fs/proc/vmcore.c:317
Inline: False
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffffffff815b7820-ffffffff815b7b98: __read_vmcore (STB_LOCAL)
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
In fs/proc/vmcore.c (ffff80001044f49c)
Location: fs/proc/vmcore.c:295
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
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
In fs/proc/vmcore.c (c0612848)
Location: fs/proc/vmcore.c:295
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
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
In fs/proc/vmcore.c (c00000000056722c)
Location: fs/proc/vmcore.c:295
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
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
In fs/proc/vmcore.c (ffffffff81379b88)
Location: fs/proc/vmcore.c:295
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
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
In fs/proc/vmcore.c (ffffffff8136a658)
Location: fs/proc/vmcore.c:295
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
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
In fs/proc/vmcore.c (ffffffff81377658)
Location: fs/proc/vmcore.c:295
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
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
In fs/proc/vmcore.c (ffffffff8138b108)
Location: fs/proc/vmcore.c:295
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
