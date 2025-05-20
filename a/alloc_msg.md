# Function: <code>alloc_msg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct msg_msg *alloc_msg(size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff813255f0)
Location: ipc/msgutil.c:51
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
```
**Symbols:**

```
ffffffff813255f0-ffffffff813256a9: alloc_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct msg_msg *alloc_msg(size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff8135a1e0)
Location: ipc/msgutil.c:49
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
```
**Symbols:**

```
ffffffff8135a1e0-ffffffff8135a299: alloc_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct msg_msg *alloc_msg(size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff813706c0)
Location: ipc/msgutil.c:49
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
```
**Symbols:**

```
ffffffff813706c0-ffffffff81370779: alloc_msg (STB_LOCAL)
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
In ipc/msgutil.c (ffffffff81383aa5)
Location: ipc/msgutil.c:49
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
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
In ipc/msgutil.c (ffffffff813a7f15)
Location: ipc/msgutil.c:49
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
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
In ipc/msgutil.c (ffffffff813d7305)
Location: ipc/msgutil.c:49
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
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
In ipc/msgutil.c (ffffffff813f1915)
Location: ipc/msgutil.c:49
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
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
In ipc/msgutil.c (ffffffff8141dbe5)
Location: ipc/msgutil.c:46
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
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
In ipc/msgutil.c (ffffffff81437a35)
Location: ipc/msgutil.c:46
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct msg_msg *alloc_msg(size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff814877b0)
Location: ipc/msgutil.c:46
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
```
**Symbols:**

```
ffffffff814877b0-ffffffff8148788c: alloc_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct msg_msg *alloc_msg(size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff814a4dd0)
Location: ipc/msgutil.c:46
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
```
**Symbols:**

```
ffffffff814a4dd0-ffffffff814a4eac: alloc_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct msg_msg *alloc_msg(size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff814aad90)
Location: ipc/msgutil.c:46
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
```
**Symbols:**

```
ffffffff814aad90-ffffffff814aae5a: alloc_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct msg_msg *alloc_msg(size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff81503250)
Location: ipc/msgutil.c:46
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
```
**Symbols:**

```
ffffffff81503250-ffffffff8150331a: alloc_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct msg_msg *alloc_msg(size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff815948c0)
Location: ipc/msgutil.c:46
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
```
**Symbols:**

```
ffffffff815948c0-ffffffff81594992: alloc_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct msg_msg *alloc_msg(size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff8163d560)
Location: ipc/msgutil.c:46
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
```
**Symbols:**

```
ffffffff8163d560-ffffffff8163d632: alloc_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct msg_msg *alloc_msg(size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff81675a60)
Location: ipc/msgutil.c:46
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
```
**Symbols:**

```
ffffffff81675a60-ffffffff81675b32: alloc_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct msg_msg *alloc_msg(size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff816b1e20)
Location: ipc/msgutil.c:46
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
```
**Symbols:**

```
ffffffff816b1e20-ffffffff816b1ef2: alloc_msg (STB_LOCAL)
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
In ipc/msgutil.c (ffff80001051e600)
Location: ipc/msgutil.c:46
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
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
In ipc/msgutil.c (c06da6d8)
Location: ipc/msgutil.c:46
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
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
In ipc/msgutil.c (c000000000667810)
Location: ipc/msgutil.c:46
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
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
In ipc/msgutil.c (ffffffe000385910)
Location: ipc/msgutil.c:46
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
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
In ipc/msgutil.c (ffffffff81430015)
Location: ipc/msgutil.c:46
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
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
In ipc/msgutil.c (ffffffff81420a95)
Location: ipc/msgutil.c:46
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
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
In ipc/msgutil.c (ffffffff8142c1b5)
Location: ipc/msgutil.c:46
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
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
In ipc/msgutil.c (ffffffff814431c5)
Location: ipc/msgutil.c:46
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
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
