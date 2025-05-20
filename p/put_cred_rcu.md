# Function: <code>put_cred_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void put_cred_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810a1ed0)
Location: kernel/cred.c:95
Inline: False
```
**Symbols:**

```
ffffffff810a1ed0-ffffffff810a1f80: put_cred_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void put_cred_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810a5680)
Location: kernel/cred.c:95
Inline: False
```
**Symbols:**

```
ffffffff810a5680-ffffffff810a572c: put_cred_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void put_cred_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810ab2e0)
Location: kernel/cred.c:95
Inline: False
```
**Symbols:**

```
ffffffff810ab2e0-ffffffff810ab38c: put_cred_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void put_cred_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810a7ea0)
Location: kernel/cred.c:96
Inline: False
```
**Symbols:**

```
ffffffff810a7ea0-ffffffff810a7f50: put_cred_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void put_cred_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810ae670)
Location: kernel/cred.c:96
Inline: False
```
**Symbols:**

```
ffffffff810ae670-ffffffff810ae720: put_cred_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void put_cred_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cred.c (0)
Location: kernel/cred.c:96
Inline: False
```
**Symbols:**

```
ffffffff810b54e0-ffffffff810b557f: put_cred_rcu (STB_LOCAL)
ffffffff810b5d1a-ffffffff810b5d2f: put_cred_rcu.cold.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void put_cred_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cred.c (0)
Location: kernel/cred.c:97
Inline: False
```
**Symbols:**

```
ffffffff810be640-ffffffff810be6df: put_cred_rcu (STB_LOCAL)
ffffffff810befa5-ffffffff810befba: put_cred_rcu.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void put_cred_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cred.c (0)
Location: kernel/cred.c:93
Inline: False
Direct callers:
  - kernel/cred.c:__put_cred
```
**Symbols:**

```
ffffffff810c4600-ffffffff810c469f: put_cred_rcu (STB_LOCAL)
ffffffff810c50b4-ffffffff810c50c9: put_cred_rcu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void put_cred_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cred.c (0)
Location: kernel/cred.c:93
Inline: False
```
**Symbols:**

```
ffffffff810cd710-ffffffff810cd7af: put_cred_rcu (STB_LOCAL)
ffffffff810ce1b4-ffffffff810ce1c9: put_cred_rcu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void put_cred_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cred.c (0)
Location: kernel/cred.c:93
Inline: False
Direct callers:
  - kernel/cred.c:__put_cred
```
**Symbols:**

```
ffffffff810d73b0-ffffffff810d744f: put_cred_rcu (STB_LOCAL)
ffffffff810d7f83-ffffffff810d7f98: put_cred_rcu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void put_cred_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cred.c (0)
Location: kernel/cred.c:93
Inline: False
Direct callers:
  - kernel/cred.c:__put_cred
```
**Symbols:**

```
ffffffff810d2280-ffffffff810d2342: put_cred_rcu (STB_LOCAL)
ffffffff81bdc2a3-ffffffff81bdc2b8: put_cred_rcu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void put_cred_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cred.c (0)
Location: kernel/cred.c:94
Inline: False
Direct callers:
  - kernel/cred.c:__put_cred
```
**Symbols:**

```
ffffffff810d3e60-ffffffff810d3f30: put_cred_rcu (STB_LOCAL)
ffffffff81bce3c6-ffffffff81bce3db: put_cred_rcu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void put_cred_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cred.c (0)
Location: kernel/cred.c:94
Inline: False
Direct callers:
  - kernel/cred.c:__put_cred
```
**Symbols:**

```
ffffffff810e6fe0-ffffffff810e70b0: put_cred_rcu (STB_LOCAL)
ffffffff81ca5704-ffffffff81ca5719: put_cred_rcu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void put_cred_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cred.c (0)
Location: kernel/cred.c:94
Inline: False
Direct callers:
  - kernel/cred.c:__put_cred
```
**Symbols:**

```
ffffffff811012c0-ffffffff8110139c: put_cred_rcu (STB_LOCAL)
ffffffff81e54fa7-ffffffff81e54fbc: put_cred_rcu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void put_cred_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff81126410)
Location: kernel/cred.c:94
Inline: False
Direct callers:
  - kernel/cred.c:__put_cred
```
**Symbols:**

```
ffffffff81126410-ffffffff81126501: put_cred_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void put_cred_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff811338c0)
Location: kernel/cred.c:94
Inline: False
Direct callers:
  - kernel/cred.c:__put_cred
```
**Symbols:**

```
ffffffff811338c0-ffffffff811339b1: put_cred_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void put_cred_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff8113e820)
Location: kernel/cred.c:68
Inline: False
Direct callers:
  - kernel/cred.c:__put_cred
```
**Symbols:**

```
ffffffff8113e820-ffffffff8113e92d: put_cred_rcu (STB_LOCAL)
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
void put_cred_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffff80001012cc20)
Location: kernel/cred.c:93
Inline: False
Direct callers:
  - kernel/cred.c:__put_cred
```
**Symbols:**

```
ffff80001012cc20-ffff80001012cd3c: put_cred_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void put_cred_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (c037cbcc)
Location: kernel/cred.c:93
Inline: False
Direct callers:
  - kernel/cred.c:__put_cred
```
**Symbols:**

```
c037cbcc-c037ccd0: put_cred_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void put_cred_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (c000000000175830)
Location: kernel/cred.c:93
Inline: False
Direct callers:
  - kernel/cred.c:__put_cred
```
**Symbols:**

```
c000000000175830-c0000000001759ac: put_cred_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void put_cred_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffe0000e1208)
Location: kernel/cred.c:93
Inline: False
Direct callers:
  - kernel/cred.c:__put_cred
```
**Symbols:**

```
ffffffe0000e1208-ffffffe0000e12ec: put_cred_rcu (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void put_cred_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cred.c (0)
Location: kernel/cred.c:93
Inline: False
```
**Symbols:**

```
ffffffff810c7a90-ffffffff810c7b2f: put_cred_rcu (STB_LOCAL)
ffffffff810c8534-ffffffff810c8549: put_cred_rcu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void put_cred_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cred.c (0)
Location: kernel/cred.c:93
Inline: False
```
**Symbols:**

```
ffffffff810b62b0-ffffffff810b634f: put_cred_rcu (STB_LOCAL)
ffffffff810b6d54-ffffffff810b6d69: put_cred_rcu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void put_cred_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cred.c (0)
Location: kernel/cred.c:93
Inline: False
```
**Symbols:**

```
ffffffff810c6fe0-ffffffff810c707f: put_cred_rcu (STB_LOCAL)
ffffffff810c7a67-ffffffff810c7a7c: put_cred_rcu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void put_cred_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cred.c (0)
Location: kernel/cred.c:93
Inline: False
```
**Symbols:**

```
ffffffff810cf4a0-ffffffff810cf53f: put_cred_rcu (STB_LOCAL)
ffffffff810cff54-ffffffff810cff69: put_cred_rcu.cold (STB_LOCAL)
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
