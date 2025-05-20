# Function: <code>serdev_device_open</code>

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
int serdev_device_open(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81609370)
Location: drivers/tty/serdev/core.c:118
Inline: False
```
**Symbols:**

```
ffffffff81609370-ffffffff816093a2: serdev_device_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int serdev_device_open(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81642f20)
Location: drivers/tty/serdev/core.c:143
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
**Symbols:**

```
ffffffff81642ad0-ffffffff81642b02: serdev_device_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int serdev_device_open(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81660ff0)
Location: drivers/tty/serdev/core.c:146
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
**Symbols:**

```
ffffffff81660ff0-ffffffff816610a5: serdev_device_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int serdev_device_open(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81697160)
Location: drivers/tty/serdev/core.c:146
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
**Symbols:**

```
ffffffff81697160-ffffffff816971f2: serdev_device_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int serdev_device_open(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff816b9d10)
Location: drivers/tty/serdev/core.c:146
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
**Symbols:**

```
ffffffff816b9d10-ffffffff816b9da2: serdev_device_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int serdev_device_open(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff8176d990)
Location: drivers/tty/serdev/core.c:147
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
**Symbols:**

```
ffffffff8176d990-ffffffff8176da22: serdev_device_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int serdev_device_open(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81788370)
Location: drivers/tty/serdev/core.c:147
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
**Symbols:**

```
ffffffff81788370-ffffffff81788402: serdev_device_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int serdev_device_open(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff8176bcc0)
Location: drivers/tty/serdev/core.c:147
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
**Symbols:**

```
ffffffff8176bcc0-ffffffff8176bd52: serdev_device_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int serdev_device_open(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff817f13f0)
Location: drivers/tty/serdev/core.c:147
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
**Symbols:**

```
ffffffff817f13f0-ffffffff817f1482: serdev_device_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int serdev_device_open(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff819319f0)
Location: drivers/tty/serdev/core.c:147
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
**Symbols:**

```
ffffffff819319f0-ffffffff81931a90: serdev_device_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int serdev_device_open(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81a90370)
Location: drivers/tty/serdev/core.c:147
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
**Symbols:**

```
ffffffff81a90370-ffffffff81a90410: serdev_device_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int serdev_device_open(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81adbb80)
Location: drivers/tty/serdev/core.c:147
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
**Symbols:**

```
ffffffff81adbb80-ffffffff81adbc20: serdev_device_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int serdev_device_open(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81b2eee0)
Location: drivers/tty/serdev/core.c:149
Inline: False
```
**Symbols:**

```
ffffffff81b2eee0-ffffffff81b2ef80: serdev_device_open (STB_GLOBAL)
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
int serdev_device_open(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffff8000108a9f88)
Location: drivers/tty/serdev/core.c:146
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
**Symbols:**

```
ffff8000108a9f88-ffff8000108aa054: serdev_device_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int serdev_device_open(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (c09a6460)
Location: drivers/tty/serdev/core.c:146
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
**Symbols:**

```
c09a6460-c09a6520: serdev_device_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int serdev_device_open(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (c000000000940860)
Location: drivers/tty/serdev/core.c:146
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
**Symbols:**

```
c000000000940860-c000000000940960: serdev_device_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int serdev_device_open(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffe00055ea98)
Location: drivers/tty/serdev/core.c:146
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
**Symbols:**

```
ffffffe00055ea98-ffffffe00055eb16: serdev_device_open (STB_GLOBAL)
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
int serdev_device_open(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff8167f770)
Location: drivers/tty/serdev/core.c:146
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
**Symbols:**

```
ffffffff8167f770-ffffffff8167f802: serdev_device_open (STB_GLOBAL)
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
int serdev_device_open(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff816adb50)
Location: drivers/tty/serdev/core.c:146
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
**Symbols:**

```
ffffffff816adb50-ffffffff816adbe2: serdev_device_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int serdev_device_open(struct serdev_device *serdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff816c7fb0)
Location: drivers/tty/serdev/core.c:146
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
**Symbols:**

```
ffffffff816c7fb0-ffffffff816c8042: serdev_device_open (STB_GLOBAL)
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
