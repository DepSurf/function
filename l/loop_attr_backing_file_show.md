# Function: <code>loop_attr_backing_file_show</code>

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
In drivers/block/loop.c (ffffffff815705b8)
Location: drivers/block/loop.c:772
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
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
In drivers/block/loop.c (ffffffff815c5ec8)
Location: drivers/block/loop.c:767
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
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
In drivers/block/loop.c (ffffffff815f4428)
Location: drivers/block/loop.c:743
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
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
In drivers/block/loop.c (ffffffff81608758)
Location: drivers/block/loop.c:766
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
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
In drivers/block/loop.c (ffffffff8166fe58)
Location: drivers/block/loop.c:755
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
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
In drivers/block/loop.c (ffffffff816abe88)
Location: drivers/block/loop.c:805
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
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
In drivers/block/loop.c (ffffffff816ccbd8)
Location: drivers/block/loop.c:802
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
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
In drivers/block/loop.c (ffffffff81708215)
Location: drivers/block/loop.c:802
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
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
In drivers/block/loop.c (ffffffff8172c465)
Location: drivers/block/loop.c:812
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t loop_attr_backing_file_show(struct loop_device *lo, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817e8420)
Location: drivers/block/loop.c:827
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
**Symbols:**

```
ffffffff817e8420-ffffffff817e84bb: loop_attr_backing_file_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t loop_attr_backing_file_show(struct loop_device *lo, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817fd6b0)
Location: drivers/block/loop.c:825
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
**Symbols:**

```
ffffffff817fd6b0-ffffffff817fd74b: loop_attr_backing_file_show (STB_LOCAL)
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
In drivers/block/loop.c (ffffffff817e352c)
Location: drivers/block/loop.c:838
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
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
In drivers/block/loop.c (ffffffff8186fa3c)
Location: drivers/block/loop.c:864
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t loop_attr_backing_file_show(struct loop_device *lo, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff819b5570)
Location: drivers/block/loop.c:669
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
**Symbols:**

```
ffffffff819b5570-ffffffff819b5608: loop_attr_backing_file_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t loop_attr_backing_file_show(struct loop_device *lo, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81b2a870)
Location: drivers/block/loop.c:669
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
**Symbols:**

```
ffffffff81b2a870-ffffffff81b2a908: loop_attr_backing_file_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t loop_attr_backing_file_show(struct loop_device *lo, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81b7ab50)
Location: drivers/block/loop.c:669
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
**Symbols:**

```
ffffffff81b7ab50-ffffffff81b7abe6: loop_attr_backing_file_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t loop_attr_backing_file_show(struct loop_device *lo, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81bce920)
Location: drivers/block/loop.c:665
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
**Symbols:**

```
ffffffff81bce920-ffffffff81bce9b6: loop_attr_backing_file_show (STB_LOCAL)
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
In drivers/block/loop.c (ffff800010922148)
Location: drivers/block/loop.c:812
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
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
In drivers/block/loop.c (c0a05f74)
Location: drivers/block/loop.c:812
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
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
In drivers/block/loop.c (c0000000009c7a08)
Location: drivers/block/loop.c:812
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
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
In drivers/block/loop.c (ffffffe0005a10fc)
Location: drivers/block/loop.c:812
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
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
In drivers/block/loop.c (ffffffff816f2245)
Location: drivers/block/loop.c:812
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
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
In drivers/block/loop.c (ffffffff816cc345)
Location: drivers/block/loop.c:812
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
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
In drivers/block/loop.c (ffffffff8171f925)
Location: drivers/block/loop.c:812
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
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
In drivers/block/loop.c (ffffffff81739945)
Location: drivers/block/loop.c:812
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
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
