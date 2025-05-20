# Function: <code>relay_remove_buf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void relay_remove_buf(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8113d200)
Location: kernel/relay.c:231
Inline: False
Direct callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
```
**Symbols:**

```
ffffffff8113d200-ffffffff8113d217: relay_remove_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void relay_remove_buf(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff81145740)
Location: kernel/relay.c:231
Inline: False
Direct callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
```
**Symbols:**

```
ffffffff81145740-ffffffff81145757: relay_remove_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void relay_remove_buf(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8114f8c0)
Location: kernel/relay.c:231
Inline: False
Direct callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
```
**Symbols:**

```
ffffffff8114f8c0-ffffffff8114f8d4: relay_remove_buf (STB_LOCAL)
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
In kernel/relay.c (ffffffff81151ca9)
Location: kernel/relay.c:231
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void relay_remove_buf(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8115ea30)
Location: kernel/relay.c:231
Inline: False
Direct callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
```
**Symbols:**

```
ffffffff8115ea30-ffffffff8115ea44: relay_remove_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void relay_remove_buf(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8116d910)
Location: kernel/relay.c:232
Inline: False
Direct callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
```
**Symbols:**

```
ffffffff8116d910-ffffffff8116d924: relay_remove_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void relay_remove_buf(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8117b350)
Location: kernel/relay.c:232
Inline: False
Direct callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
```
**Symbols:**

```
ffffffff8117b350-ffffffff8117b364: relay_remove_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void relay_remove_buf(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff81187e80)
Location: kernel/relay.c:232
Inline: False
Direct callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
```
**Symbols:**

```
ffffffff81187e80-ffffffff81187e94: relay_remove_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void relay_remove_buf(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff81193dc0)
Location: kernel/relay.c:232
Inline: False
Direct callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
```
**Symbols:**

```
ffffffff81193dc0-ffffffff81193dd4: relay_remove_buf (STB_LOCAL)
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
In kernel/relay.c (ffffffff811a8bb7)
Location: kernel/relay.c:233
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
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
In kernel/relay.c (ffffffff811a63a7)
Location: kernel/relay.c:221
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
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
In kernel/relay.c (ffffffff811a72c7)
Location: kernel/relay.c:221
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
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
In kernel/relay.c (ffffffff811d0b57)
Location: kernel/relay.c:221
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
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
In kernel/relay.c (ffffffff81204fe1)
Location: kernel/relay.c:221
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
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
In kernel/relay.c (ffffffff8124ce61)
Location: kernel/relay.c:218
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
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
In kernel/relay.c (ffffffff81264401)
Location: kernel/relay.c:218
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
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
In kernel/relay.c (ffffffff8127e1f1)
Location: kernel/relay.c:218
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
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
In kernel/relay.c (ffff80001020c044)
Location: kernel/relay.c:232
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
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
In kernel/relay.c (c044a918)
Location: kernel/relay.c:232
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
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
In kernel/relay.c (c0000000002892fc)
Location: kernel/relay.c:232
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
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
In kernel/relay.c (ffffffe00016d5fa)
Location: kernel/relay.c:232
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
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
void relay_remove_buf(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8118c3e0)
Location: kernel/relay.c:232
Inline: False
Direct callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
```
**Symbols:**

```
ffffffff8118c3e0-ffffffff8118c3f4: relay_remove_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void relay_remove_buf(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8117f4c0)
Location: kernel/relay.c:232
Inline: False
Direct callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
```
**Symbols:**

```
ffffffff8117f4c0-ffffffff8117f4d4: relay_remove_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void relay_remove_buf(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8118a1b0)
Location: kernel/relay.c:232
Inline: False
Direct callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
```
**Symbols:**

```
ffffffff8118a1b0-ffffffff8118a1c4: relay_remove_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void relay_remove_buf(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff81197b20)
Location: kernel/relay.c:232
Inline: False
Direct callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
```
**Symbols:**

```
ffffffff81197b20-ffffffff81197b34: relay_remove_buf (STB_LOCAL)
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
