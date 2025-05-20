# Function: <code>hibernation_restore</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int hibernation_restore(int platform_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810cf800)
Location: kernel/power/hibernate.c:494
Inline: True
```
**Symbols:**

```
ffffffff810cf800-ffffffff810cf91a: hibernation_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int hibernation_restore(int platform_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810d42b0)
Location: kernel/power/hibernate.c:501
Inline: True
Direct callers:
  - kernel/power/hibernate.c:load_image_and_restore
```
**Symbols:**

```
ffffffff810d42b0-ffffffff810d43ca: hibernation_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int hibernation_restore(int platform_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810dae60)
Location: kernel/power/hibernate.c:503
Inline: True
Direct callers:
  - kernel/power/hibernate.c:load_image_and_restore
```
**Symbols:**

```
ffffffff810dae60-ffffffff810daf7a: hibernation_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int hibernation_restore(int platform_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810d9f70)
Location: kernel/power/hibernate.c:501
Inline: True
Direct callers:
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff810d9f70-ffffffff810da08a: hibernation_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int hibernation_restore(int platform_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810e21d0)
Location: kernel/power/hibernate.c:501
Inline: True
Direct callers:
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff810e21d0-ffffffff810e22fc: hibernation_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hibernation_restore(int platform_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:506
Inline: True
Direct callers:
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff810ead24-ffffffff810ead35: hibernation_restore.cold.7 (STB_LOCAL)
ffffffff810ea5c0-ffffffff810ea6ff: hibernation_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hibernation_restore(int platform_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:507
Inline: True
Direct callers:
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff810f6357-ffffffff810f6368: hibernation_restore.cold.9 (STB_LOCAL)
ffffffff810f5bf0-ffffffff810f5d2f: hibernation_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hibernation_restore(int platform_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:514
Inline: True
Direct callers:
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff810fe8f4-ffffffff810fe905: hibernation_restore.cold (STB_LOCAL)
ffffffff810fe170-ffffffff810fe2b4: hibernation_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hibernation_restore(int platform_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:515
Inline: True
Direct callers:
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff8110ad40-ffffffff8110ad51: hibernation_restore.cold (STB_LOCAL)
ffffffff8110a5a0-ffffffff8110a6e4: hibernation_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hibernation_restore(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff811152f0)
Location: kernel/power/hibernate.c:527
Inline: False
Direct callers:
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff811152f0-ffffffff81115357: hibernation_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hibernation_restore(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81111c80)
Location: kernel/power/hibernate.c:527
Inline: False
Direct callers:
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff81111c80-ffffffff81111ce7: hibernation_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int hibernation_restore(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:527
Inline: False
Direct callers:
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff81bd1322-ffffffff81bd1333: hibernation_restore.cold (STB_LOCAL)
ffffffff811125d0-ffffffff81112703: hibernation_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hibernation_restore(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:530
Inline: False
Direct callers:
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff81ca9e8b-ffffffff81ca9e9c: hibernation_restore.cold (STB_LOCAL)
ffffffff81132600-ffffffff81132733: hibernation_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hibernation_restore(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81154520)
Location: kernel/power/hibernate.c:531
Inline: False
Direct callers:
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff81154520-ffffffff8115458c: hibernation_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hibernation_restore(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81183d40)
Location: kernel/power/hibernate.c:535
Inline: False
Direct callers:
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff81183d40-ffffffff81183dac: hibernation_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hibernation_restore(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81194bb0)
Location: kernel/power/hibernate.c:536
Inline: False
Direct callers:
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff81194bb0-ffffffff81194c1c: hibernation_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hibernation_restore(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff811a35a0)
Location: kernel/power/hibernate.c:536
Inline: False
Direct callers:
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff811a35a0-ffffffff811a360c: hibernation_restore (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int hibernation_restore(int platform_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (c03bcca4)
Location: kernel/power/hibernate.c:515
Inline: True
Direct callers:
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
c03bcca4-c03bce04: hibernation_restore (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hibernation_restore(int platform_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:515
Inline: True
Direct callers:
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff81102fa0-ffffffff81102fb1: hibernation_restore.cold (STB_LOCAL)
ffffffff81102800-ffffffff81102944: hibernation_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hibernation_restore(int platform_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:515
Inline: True
Direct callers:
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff810f4200-ffffffff810f4211: hibernation_restore.cold (STB_LOCAL)
ffffffff810f3a80-ffffffff810f3bb5: hibernation_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hibernation_restore(int platform_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:515
Inline: True
Direct callers:
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff81101210-ffffffff81101221: hibernation_restore.cold (STB_LOCAL)
ffffffff81100a70-ffffffff81100bb4: hibernation_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hibernation_restore(int platform_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:515
Inline: True
Direct callers:
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff8110c5e0-ffffffff8110c5f1: hibernation_restore.cold (STB_LOCAL)
ffffffff8110be40-ffffffff8110bf84: hibernation_restore (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
