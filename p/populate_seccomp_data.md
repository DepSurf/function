# Function: <code>populate_seccomp_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void populate_seccomp_data(struct seccomp_data *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8113b560)
Location: kernel/seccomp.c:70
Inline: False
```
**Symbols:**

```
ffffffff8113b560-ffffffff8113b605: populate_seccomp_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void populate_seccomp_data(struct seccomp_data *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81143ac0)
Location: kernel/seccomp.c:70
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81143ac0-ffffffff81143b65: populate_seccomp_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void populate_seccomp_data(struct seccomp_data *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8114d990)
Location: kernel/seccomp.c:69
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff8114d990-ffffffff8114da33: populate_seccomp_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void populate_seccomp_data(struct seccomp_data *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8114fdc0)
Location: kernel/seccomp.c:75
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_run_filters
```
**Symbols:**

```
ffffffff8114fdc0-ffffffff8114fe63: populate_seccomp_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void populate_seccomp_data(struct seccomp_data *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8115c390)
Location: kernel/seccomp.c:76
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_run_filters
```
**Symbols:**

```
ffffffff8115c390-ffffffff8115c42d: populate_seccomp_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void populate_seccomp_data(struct seccomp_data *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8116acb0)
Location: kernel/seccomp.c:78
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_run_filters
```
**Symbols:**

```
ffffffff8116acb0-ffffffff8116ad4d: populate_seccomp_data (STB_LOCAL)
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
In kernel/seccomp.c (ffffffff81178e01)
Location: kernel/seccomp.c:144
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff81185b04)
Location: kernel/seccomp.c:144
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff81191a7f)
Location: kernel/seccomp.c:145
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void populate_seccomp_data(struct seccomp_data *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a53b0)
Location: kernel/seccomp.c:153
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff811a53b0-ffffffff811a5450: populate_seccomp_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void populate_seccomp_data(struct seccomp_data *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a2310)
Location: kernel/seccomp.c:231
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff811a2310-ffffffff811a23b0: populate_seccomp_data (STB_LOCAL)
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
In kernel/seccomp.c (ffffffff811a4944)
Location: kernel/seccomp.c:236
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void populate_seccomp_data(struct seccomp_data *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811cdaa0)
Location: kernel/seccomp.c:239
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff811cdaa0-ffffffff811cdb40: populate_seccomp_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void populate_seccomp_data(struct seccomp_data *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81201a90)
Location: kernel/seccomp.c:241
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81201a90-ffffffff81201b47: populate_seccomp_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void populate_seccomp_data(struct seccomp_data *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81249870)
Location: kernel/seccomp.c:241
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81249870-ffffffff81249927: populate_seccomp_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void populate_seccomp_data(struct seccomp_data *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8125f780)
Location: kernel/seccomp.c:241
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff8125f780-ffffffff8125f837: populate_seccomp_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void populate_seccomp_data(struct seccomp_data *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81279790)
Location: kernel/seccomp.c:246
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81279790-ffffffff81279847: populate_seccomp_data (STB_LOCAL)
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
In kernel/seccomp.c (ffff80001020944c)
Location: kernel/seccomp.c:145
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (c04481a4)
Location: kernel/seccomp.c:145
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (c000000000286500)
Location: kernel/seccomp.c:145
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffe00016b4e4)
Location: kernel/seccomp.c:145
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff8118a09f)
Location: kernel/seccomp.c:145
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff8117d1cf)
Location: kernel/seccomp.c:145
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff81187e6f)
Location: kernel/seccomp.c:145
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff811957c3)
Location: kernel/seccomp.c:145
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
