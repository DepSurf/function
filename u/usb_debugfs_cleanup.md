# Function: <code>usb_debugfs_cleanup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void usb_debugfs_cleanup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff816f558f)
Location: drivers/usb/core/usb.c:1036
Inline: False
```
**Symbols:**

```
ffffffff816f558f-ffffffff816f55b2: usb_debugfs_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void usb_debugfs_cleanup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff8175a20e)
Location: drivers/usb/core/usb.c:1041
Inline: False
```
**Symbols:**

```
ffffffff8175a20e-ffffffff8175a231: usb_debugfs_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void usb_debugfs_cleanup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81786707)
Location: drivers/usb/core/usb.c:1055
Inline: False
```
**Symbols:**

```
ffffffff81786707-ffffffff8178672a: usb_debugfs_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void usb_debugfs_cleanup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff816a69a2)
Location: drivers/usb/core/usb.c:1191
Inline: False
```
**Symbols:**

```
ffffffff816a69a2-ffffffff816a69c5: usb_debugfs_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void usb_debugfs_cleanup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81711d75)
Location: drivers/usb/core/usb.c:1191
Inline: False
```
**Symbols:**

```
ffffffff81711d75-ffffffff81711d98: usb_debugfs_cleanup (STB_LOCAL)
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
In drivers/usb/core/usb.c (ffffffff82907d20)
Location: drivers/usb/core/usb.c:1179
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
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
In drivers/usb/core/usb.c (ffffffff82adfb44)
Location: drivers/usb/core/usb.c:1179
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
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
In drivers/usb/core/usb.c (ffffffff82b04be6)
Location: drivers/usb/core/usb.c:1196
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
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
In drivers/usb/core/usb.c (ffffffff82b13b5e)
Location: drivers/usb/core/usb.c:974
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
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
In drivers/usb/core/usb.c (ffffffff82f2560f)
Location: drivers/usb/core/usb.c:974
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
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
In drivers/usb/core/usb.c (ffffffff8321db7c)
Location: drivers/usb/core/usb.c:993
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void usb_debugfs_cleanup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81c0c6f5)
Location: drivers/usb/core/usb.c:1037
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
```
**Symbols:**

```
ffffffff81c0c6f5-ffffffff81c0c71b: usb_debugfs_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void usb_debugfs_cleanup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81d13606)
Location: drivers/usb/core/usb.c:1037
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
```
**Symbols:**

```
ffffffff81d13606-ffffffff81d1362c: usb_debugfs_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void usb_debugfs_cleanup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81ede3f0)
Location: drivers/usb/core/usb.c:999
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
```
**Symbols:**

```
ffffffff81ede3f0-ffffffff81ede420: usb_debugfs_cleanup (STB_LOCAL)
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
In drivers/usb/core/usb.c (ffffffff842b204a)
Location: drivers/usb/core/usb.c:999
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
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
In drivers/usb/core/usb.c (ffffffff83af4d2a)
Location: drivers/usb/core/usb.c:1075
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
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
In drivers/usb/core/usb.c (ffffffff83d50ad6)
Location: drivers/usb/core/usb.c:1063
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
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
In drivers/usb/core/usb.c (ffff8000114ba630)
Location: drivers/usb/core/usb.c:974
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
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
In drivers/usb/core/usb.c (c15c0798)
Location: drivers/usb/core/usb.c:974
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
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
In drivers/usb/core/usb.c (c0000000013cdf0c)
Location: drivers/usb/core/usb.c:974
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
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
In drivers/usb/core/usb.c (ffffffe0000a20e0)
Location: drivers/usb/core/usb.c:974
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
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
In drivers/usb/core/usb.c (ffffffff82af3b06)
Location: drivers/usb/core/usb.c:974
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
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
In drivers/usb/core/usb.c (ffffffff82ac3fad)
Location: drivers/usb/core/usb.c:974
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
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
In drivers/usb/core/usb.c (ffffffff82b0ee74)
Location: drivers/usb/core/usb.c:974
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
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
In drivers/usb/core/usb.c (ffffffff82b03996)
Location: drivers/usb/core/usb.c:974
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
