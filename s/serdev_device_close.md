# Function: <code>serdev_device_close</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void serdev_device_close(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff816093b0)
Location: drivers/tty/serdev/core.c:129
Inline: False
```
**Symbols:**

```
ffffffff816093b0-ffffffff816093de: serdev_device_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void serdev_device_close(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81642b45)
Location: drivers/tty/serdev/core.c:154
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_release
```
**Symbols:**

```
ffffffff81642b10-ffffffff81642b3d: serdev_device_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void serdev_device_close(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff816610b0)
Location: drivers/tty/serdev/core.c:174
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_release
```
**Symbols:**

```
ffffffff816610b0-ffffffff816610f7: serdev_device_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void serdev_device_close(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81696b70)
Location: drivers/tty/serdev/core.c:174
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_release
```
**Symbols:**

```
ffffffff81696b70-ffffffff81696bbb: serdev_device_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void serdev_device_close(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff816b9700)
Location: drivers/tty/serdev/core.c:174
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_release
```
**Symbols:**

```
ffffffff816b9700-ffffffff816b974b: serdev_device_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void serdev_device_close(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff8176e3a5)
Location: drivers/tty/serdev/core.c:175
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_release
```
**Symbols:**

```
ffffffff8176da30-ffffffff8176da7d: serdev_device_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void serdev_device_close(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81788d85)
Location: drivers/tty/serdev/core.c:175
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_release
```
**Symbols:**

```
ffffffff81788410-ffffffff8178845d: serdev_device_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void serdev_device_close(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff8176c675)
Location: drivers/tty/serdev/core.c:175
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_release
```
**Symbols:**

```
ffffffff8176bd60-ffffffff8176bdad: serdev_device_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void serdev_device_close(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff817f1dc5)
Location: drivers/tty/serdev/core.c:175
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_release
```
**Symbols:**

```
ffffffff817f1490-ffffffff817f14dd: serdev_device_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void serdev_device_close(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff819324f5)
Location: drivers/tty/serdev/core.c:175
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_release
```
**Symbols:**

```
ffffffff81931a90-ffffffff81931ae4: serdev_device_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void serdev_device_close(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81a91025)
Location: drivers/tty/serdev/core.c:175
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_release
```
**Symbols:**

```
ffffffff81a90420-ffffffff81a90474: serdev_device_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void serdev_device_close(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81adc835)
Location: drivers/tty/serdev/core.c:175
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_release
```
**Symbols:**

```
ffffffff81adbc30-ffffffff81adbc84: serdev_device_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void serdev_device_close(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81b2ef90)
Location: drivers/tty/serdev/core.c:177
Inline: True
```
**Symbols:**

```
ffffffff81b2ef90-ffffffff81b2efe4: serdev_device_close (STB_GLOBAL)
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
void serdev_device_close(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffff8000108a9440)
Location: drivers/tty/serdev/core.c:174
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_release
```
**Symbols:**

```
ffff8000108a9440-ffff8000108a9494: serdev_device_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void serdev_device_close(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (c09a5cd8)
Location: drivers/tty/serdev/core.c:174
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_release
```
**Symbols:**

```
c09a5cd8-c09a5d28: serdev_device_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void serdev_device_close(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (c000000000940960)
Location: drivers/tty/serdev/core.c:174
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_release
```
**Symbols:**

```
c000000000940960-c0000000009409dc: serdev_device_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void serdev_device_close(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffe00055eb16)
Location: drivers/tty/serdev/core.c:174
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_release
```
**Symbols:**

```
ffffffe00055eb16-ffffffe00055eb5a: serdev_device_close (STB_GLOBAL)
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
void serdev_device_close(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff8167f160)
Location: drivers/tty/serdev/core.c:174
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_release
```
**Symbols:**

```
ffffffff8167f160-ffffffff8167f1ab: serdev_device_close (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void serdev_device_close(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff816ad540)
Location: drivers/tty/serdev/core.c:174
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_release
```
**Symbols:**

```
ffffffff816ad540-ffffffff816ad58b: serdev_device_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void serdev_device_close(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff816c79a0)
Location: drivers/tty/serdev/core.c:174
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_release
```
**Symbols:**

```
ffffffff816c79a0-ffffffff816c79eb: serdev_device_close (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
