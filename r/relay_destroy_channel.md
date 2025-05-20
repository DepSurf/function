# Function: <code>relay_destroy_channel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void relay_destroy_channel(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8113c4e0)
Location: kernel/relay.c:196
Inline: False
Direct callers:
  - kernel/relay.c:relay_destroy_buf
  - kernel/relay.c:relay_close
  - kernel/relay.c:relay_open
```
**Symbols:**

```
ffffffff8113c4e0-ffffffff8113c4f4: relay_destroy_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void relay_destroy_channel(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff81144a30)
Location: kernel/relay.c:196
Inline: False
Direct callers:
  - kernel/relay.c:relay_close
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_destroy_buf
```
**Symbols:**

```
ffffffff81144a30-ffffffff81144a44: relay_destroy_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void relay_destroy_channel(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8114e8c0)
Location: kernel/relay.c:196
Inline: False
Direct callers:
  - kernel/relay.c:relay_close
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_destroy_buf
```
**Symbols:**

```
ffffffff8114e8c0-ffffffff8114e8d4: relay_destroy_channel (STB_LOCAL)
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
In kernel/relay.c (ffffffff8115261b)
Location: kernel/relay.c:196
Inline: True
Inline callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_destroy_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void relay_destroy_channel(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8115d780)
Location: kernel/relay.c:196
Inline: False
Direct callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_destroy_buf
```
**Symbols:**

```
ffffffff8115d780-ffffffff8115d794: relay_destroy_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void relay_destroy_channel(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8116c6f0)
Location: kernel/relay.c:197
Inline: False
Direct callers:
  - kernel/relay.c:relay_destroy_buf
```
**Symbols:**

```
ffffffff8116c6f0-ffffffff8116c704: relay_destroy_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void relay_destroy_channel(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8117a120)
Location: kernel/relay.c:197
Inline: False
Direct callers:
  - kernel/relay.c:relay_destroy_buf
```
**Symbols:**

```
ffffffff8117a120-ffffffff8117a134: relay_destroy_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void relay_destroy_channel(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff81186f70)
Location: kernel/relay.c:197
Inline: False
Direct callers:
  - kernel/relay.c:relay_destroy_buf
```
**Symbols:**

```
ffffffff81186f70-ffffffff81186f84: relay_destroy_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void relay_destroy_channel(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff81192e90)
Location: kernel/relay.c:197
Inline: False
Direct callers:
  - kernel/relay.c:relay_destroy_buf
```
**Symbols:**

```
ffffffff81192e90-ffffffff81192ea4: relay_destroy_channel (STB_LOCAL)
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
In kernel/relay.c (ffffffff811a8b63)
Location: kernel/relay.c:197
Inline: True
Inline callers:
  - kernel/relay.c:relay_destroy_buf
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
In kernel/relay.c (ffffffff811a6353)
Location: kernel/relay.c:185
Inline: True
Inline callers:
  - kernel/relay.c:relay_destroy_buf
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
In kernel/relay.c (ffffffff811a7193)
Location: kernel/relay.c:185
Inline: True
Inline callers:
  - kernel/relay.c:relay_destroy_buf
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
In kernel/relay.c (ffffffff811d0a00)
Location: kernel/relay.c:185
Inline: True
Inline callers:
  - kernel/relay.c:relay_destroy_buf
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
In kernel/relay.c (ffffffff812054c4)
Location: kernel/relay.c:185
Inline: True
Inline callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_destroy_buf
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
In kernel/relay.c (ffffffff8124d5a0)
Location: kernel/relay.c:182
Inline: True
Inline callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_destroy_buf
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
In kernel/relay.c (ffffffff81264920)
Location: kernel/relay.c:182
Inline: True
Inline callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_destroy_buf
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
In kernel/relay.c (ffffffff8127e747)
Location: kernel/relay.c:182
Inline: True
Inline callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_destroy_buf
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
In kernel/relay.c (ffff80001020b948)
Location: kernel/relay.c:197
Inline: True
Inline callers:
  - kernel/relay.c:relay_destroy_buf
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
In kernel/relay.c (c044a88c)
Location: kernel/relay.c:197
Inline: True
Inline callers:
  - kernel/relay.c:relay_destroy_buf
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
In kernel/relay.c (c0000000002891bc)
Location: kernel/relay.c:197
Inline: True
Inline callers:
  - kernel/relay.c:relay_destroy_buf
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
In kernel/relay.c (ffffffe00016d31a)
Location: kernel/relay.c:197
Inline: True
Inline callers:
  - kernel/relay.c:relay_destroy_buf
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
void relay_destroy_channel(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8118b4b0)
Location: kernel/relay.c:197
Inline: False
Direct callers:
  - kernel/relay.c:relay_destroy_buf
```
**Symbols:**

```
ffffffff8118b4b0-ffffffff8118b4c4: relay_destroy_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void relay_destroy_channel(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8117e5b0)
Location: kernel/relay.c:197
Inline: False
Direct callers:
  - kernel/relay.c:relay_destroy_buf
```
**Symbols:**

```
ffffffff8117e5b0-ffffffff8117e5c4: relay_destroy_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void relay_destroy_channel(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff81189280)
Location: kernel/relay.c:197
Inline: False
Direct callers:
  - kernel/relay.c:relay_destroy_buf
```
**Symbols:**

```
ffffffff81189280-ffffffff81189294: relay_destroy_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void relay_destroy_channel(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff81196bd0)
Location: kernel/relay.c:197
Inline: False
Direct callers:
  - kernel/relay.c:relay_destroy_buf
```
**Symbols:**

```
ffffffff81196bd0-ffffffff81196be4: relay_destroy_channel (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
