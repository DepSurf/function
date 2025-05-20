# Function: <code>hibernation_snapshot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int hibernation_snapshot(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810cf470)
Location: kernel/power/hibernate.c:338
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff810cf470-ffffffff810cf7ff: hibernation_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int hibernation_snapshot(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810d3f00)
Location: kernel/power/hibernate.c:339
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff810d3f00-ffffffff810d429c: hibernation_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int hibernation_snapshot(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810daa90)
Location: kernel/power/hibernate.c:341
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff810daa90-ffffffff810dae33: hibernation_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int hibernation_snapshot(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810d9b60)
Location: kernel/power/hibernate.c:340
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff810d9b60-ffffffff810d9f48: hibernation_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hibernation_snapshot(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810e1d00)
Location: kernel/power/hibernate.c:340
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff810e1d00-ffffffff810e21b0: hibernation_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int hibernation_snapshot(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:343
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff810eac6c-ffffffff810ead24: hibernation_snapshot.cold.6 (STB_LOCAL)
ffffffff810ea1d0-ffffffff810ea594: hibernation_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int hibernation_snapshot(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:343
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff810f629c-ffffffff810f6357: hibernation_snapshot.cold.8 (STB_LOCAL)
ffffffff810f5800-ffffffff810f5bc4: hibernation_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int hibernation_snapshot(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:350
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff810fe85d-ffffffff810fe8f4: hibernation_snapshot.cold (STB_LOCAL)
ffffffff810fdd10-ffffffff810fe14c: hibernation_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int hibernation_snapshot(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:351
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff8110aca9-ffffffff8110ad40: hibernation_snapshot.cold (STB_LOCAL)
ffffffff8110a140-ffffffff8110a57c: hibernation_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int hibernation_snapshot(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:363
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff811158fb-ffffffff8111593c: hibernation_snapshot.cold (STB_LOCAL)
ffffffff81114fd0-ffffffff811151c3: hibernation_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int hibernation_snapshot(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:363
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff81bdf18e-ffffffff81bdf1cf: hibernation_snapshot.cold (STB_LOCAL)
ffffffff81111970-ffffffff81111b54: hibernation_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int hibernation_snapshot(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:363
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff81bd12e1-ffffffff81bd1322: hibernation_snapshot.cold (STB_LOCAL)
ffffffff811123c0-ffffffff811125a4: hibernation_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hibernation_snapshot(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:366
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff81ca9e4a-ffffffff81ca9e8b: hibernation_snapshot.cold (STB_LOCAL)
ffffffff811323f0-ffffffff811325d4: hibernation_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hibernation_snapshot(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:365
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff81e59ec7-ffffffff81e59f11: hibernation_snapshot.cold (STB_LOCAL)
ffffffff811541c0-ffffffff811543de: hibernation_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hibernation_snapshot(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81183900)
Location: kernel/power/hibernate.c:369
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff81183900-ffffffff81183ba5: hibernation_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hibernation_snapshot(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81194770)
Location: kernel/power/hibernate.c:370
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff81194770-ffffffff81194a15: hibernation_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hibernation_snapshot(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff811a3160)
Location: kernel/power/hibernate.c:370
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff811a3160-ffffffff811a3405: hibernation_snapshot (STB_GLOBAL)
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
<summary>In <code>armhf</code>: ✅</summary>

```c
int hibernation_snapshot(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (c03bc6f4)
Location: kernel/power/hibernate.c:351
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
c03bc6f4-c03bcc84: hibernation_snapshot (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int hibernation_snapshot(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:351
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff81102f09-ffffffff81102fa0: hibernation_snapshot.cold (STB_LOCAL)
ffffffff811023a0-ffffffff811027d2: hibernation_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int hibernation_snapshot(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:351
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff810f4169-ffffffff810f4200: hibernation_snapshot.cold (STB_LOCAL)
ffffffff810f3630-ffffffff810f3a60: hibernation_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int hibernation_snapshot(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:351
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff81101179-ffffffff81101210: hibernation_snapshot.cold (STB_LOCAL)
ffffffff81100610-ffffffff81100a4c: hibernation_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int hibernation_snapshot(int platform_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:351
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff8110c549-ffffffff8110c5e0: hibernation_snapshot.cold (STB_LOCAL)
ffffffff8110b9b0-ffffffff8110be1e: hibernation_snapshot (STB_GLOBAL)
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
