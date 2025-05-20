# Function: <code>get_reqs_available</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool get_reqs_available(struct kioctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8125b350)
Location: fs/aio.c:901
Inline: False
Direct callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:do_io_submit
```
**Symbols:**

```
ffffffff8125b350-ffffffff8125b3cb: get_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool get_reqs_available(struct kioctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81283f30)
Location: fs/aio.c:911
Inline: False
Direct callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:do_io_submit
```
**Symbols:**

```
ffffffff81283f30-ffffffff81283fab: get_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool get_reqs_available(struct kioctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81297ba0)
Location: fs/aio.c:914
Inline: False
Direct callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:do_io_submit
```
**Symbols:**

```
ffffffff81297ba0-ffffffff81297c1b: get_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool get_reqs_available(struct kioctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812a59d0)
Location: fs/aio.c:919
Inline: False
Direct callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:do_io_submit
```
**Symbols:**

```
ffffffff812a59d0-ffffffff812a5a4b: get_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool get_reqs_available(struct kioctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812c8ef0)
Location: fs/aio.c:943
Inline: False
Direct callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:do_io_submit
```
**Symbols:**

```
ffffffff812c8ef0-ffffffff812c8f6b: get_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool get_reqs_available(struct kioctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812f1fe0)
Location: fs/aio.c:906
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
ffffffff812f1fe0-ffffffff812f205b: get_reqs_available (STB_LOCAL)
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
In fs/aio.c (ffffffff813094cf)
Location: fs/aio.c:1014
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
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
In fs/aio.c (ffffffff8132b567)
Location: fs/aio.c:1011
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
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
In fs/aio.c (ffffffff8133e3b7)
Location: fs/aio.c:1011
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
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
In fs/aio.c (ffffffff81378227)
Location: fs/aio.c:1011
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
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
In fs/aio.c (ffffffff81385f27)
Location: fs/aio.c:1013
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
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
In fs/aio.c (ffffffff8138d077)
Location: fs/aio.c:1010
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
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
In fs/aio.c (ffffffff813da7d7)
Location: fs/aio.c:1011
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
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
In fs/aio.c (ffffffff814651c6)
Location: fs/aio.c:1037
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
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
In fs/aio.c (ffffffff814f5206)
Location: fs/aio.c:1038
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
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
In fs/aio.c (ffffffff8152bfd6)
Location: fs/aio.c:1035
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
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
In fs/aio.c (ffffffff81560eb6)
Location: fs/aio.c:1045
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
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
In fs/aio.c (ffff8000103fd898)
Location: fs/aio.c:1011
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
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
In fs/aio.c (c05d1294)
Location: fs/aio.c:1011
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_submit
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
In fs/aio.c (c000000000506b30)
Location: fs/aio.c:1011
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
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
In fs/aio.c (ffffffe0002ab272)
Location: fs/aio.c:1011
Inline: True
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
In fs/aio.c (ffffffff81336997)
Location: fs/aio.c:1011
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
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
In fs/aio.c (ffffffff81327317)
Location: fs/aio.c:1011
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
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
In fs/aio.c (ffffffff81334467)
Location: fs/aio.c:1011
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
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
In fs/aio.c (ffffffff813468c7)
Location: fs/aio.c:1011
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
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
</ul>
