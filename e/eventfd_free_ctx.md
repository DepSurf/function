# Function: <code>eventfd_free_ctx</code>

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
In fs/eventfd.c (ffffffff812590c9)
Location: fs/eventfd.c:70
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff81281c6f)
Location: fs/eventfd.c:70
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff8129579f)
Location: fs/eventfd.c:70
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff812a28a0)
Location: fs/eventfd.c:70
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_put
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
In fs/eventfd.c (ffffffff812c5d24)
Location: fs/eventfd.c:70
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff812eef11)
Location: fs/eventfd.c:70
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff813038a1)
Location: fs/eventfd.c:70
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void eventfd_free_ctx(struct eventfd_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81324cc0)
Location: fs/eventfd.c:75
Inline: False
Direct callers:
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_release
```
**Symbols:**

```
ffffffff81324cc0-ffffffff81324ced: eventfd_free_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void eventfd_free_ctx(struct eventfd_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81337a50)
Location: fs/eventfd.c:90
Inline: False
Direct callers:
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_release
```
**Symbols:**

```
ffffffff81337a50-ffffffff81337a7d: eventfd_free_ctx (STB_LOCAL)
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
In fs/eventfd.c (ffffffff81371797)
Location: fs/eventfd.c:91
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff8137f557)
Location: fs/eventfd.c:91
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff813861d7)
Location: fs/eventfd.c:91
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff813d34a7)
Location: fs/eventfd.c:89
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff8145ca7f)
Location: fs/eventfd.c:89
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff814ec15f)
Location: fs/eventfd.c:94
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff8152331f)
Location: fs/eventfd.c:94
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff81557a51)
Location: fs/eventfd.c:82
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_release
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
void eventfd_free_ctx(struct eventfd_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffff8000103f5b78)
Location: fs/eventfd.c:90
Inline: False
Direct callers:
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_ctx_put
```
**Symbols:**

```
ffff8000103f5b78-ffff8000103f5bb8: eventfd_free_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void eventfd_free_ctx(struct eventfd_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (c05ca764)
Location: fs/eventfd.c:90
Inline: False
Direct callers:
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_ctx_put
```
**Symbols:**

```
c05ca764-c05ca7a0: eventfd_free_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void eventfd_free_ctx(struct eventfd_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (c0000000004fdca0)
Location: fs/eventfd.c:90
Inline: False
Direct callers:
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_ctx_put
```
**Symbols:**

```
c0000000004fdca0-c0000000004fdd04: eventfd_free_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void eventfd_free_ctx(struct eventfd_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffe0002a6594)
Location: fs/eventfd.c:90
Inline: False
Direct callers:
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_release
```
**Symbols:**

```
ffffffe0002a6594-ffffffe0002a65d4: eventfd_free_ctx (STB_LOCAL)
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
void eventfd_free_ctx(struct eventfd_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81330030)
Location: fs/eventfd.c:90
Inline: False
Direct callers:
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_release
```
**Symbols:**

```
ffffffff81330030-ffffffff8133005d: eventfd_free_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void eventfd_free_ctx(struct eventfd_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81320c50)
Location: fs/eventfd.c:90
Inline: False
Direct callers:
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_release
```
**Symbols:**

```
ffffffff81320c50-ffffffff81320c7d: eventfd_free_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void eventfd_free_ctx(struct eventfd_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff8132db00)
Location: fs/eventfd.c:90
Inline: False
Direct callers:
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_release
```
**Symbols:**

```
ffffffff8132db00-ffffffff8132db2d: eventfd_free_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void eventfd_free_ctx(struct eventfd_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81340470)
Location: fs/eventfd.c:90
Inline: False
Direct callers:
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_release
```
**Symbols:**

```
ffffffff81340470-ffffffff8134049d: eventfd_free_ctx (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
