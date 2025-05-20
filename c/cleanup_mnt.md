# Function: <code>cleanup_mnt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cleanup_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122cb70)
Location: fs/namespace.c:1051
Inline: False
Direct callers:
  - fs/namespace.c:delayed_mntput
  - fs/namespace.c:__cleanup_mnt
```
**Symbols:**

```
ffffffff8122cb70-ffffffff8122cbf2: cleanup_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cleanup_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81255300)
Location: fs/namespace.c:1051
Inline: False
Direct callers:
  - fs/namespace.c:delayed_mntput
  - fs/namespace.c:__cleanup_mnt
```
**Symbols:**

```
ffffffff81255300-ffffffff81255382: cleanup_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cleanup_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81268840)
Location: fs/namespace.c:1096
Inline: False
Direct callers:
  - fs/namespace.c:delayed_mntput
  - fs/namespace.c:__cleanup_mnt
```
**Symbols:**

```
ffffffff81268840-ffffffff812688c2: cleanup_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cleanup_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81275bb0)
Location: fs/namespace.c:1097
Inline: False
Direct callers:
  - fs/namespace.c:delayed_mntput
  - fs/namespace.c:__cleanup_mnt
```
**Symbols:**

```
ffffffff81275bb0-ffffffff81275c23: cleanup_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cleanup_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81298100)
Location: fs/namespace.c:1164
Inline: False
Direct callers:
  - fs/namespace.c:delayed_mntput
  - fs/namespace.c:__cleanup_mnt
```
**Symbols:**

```
ffffffff81298100-ffffffff81298173: cleanup_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cleanup_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812bdd40)
Location: fs/namespace.c:1175
Inline: False
Direct callers:
  - fs/namespace.c:delayed_mntput
  - fs/namespace.c:__cleanup_mnt
```
**Symbols:**

```
ffffffff812bdd40-ffffffff812bddab: cleanup_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cleanup_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d3030)
Location: fs/namespace.c:1087
Inline: False
Direct callers:
  - fs/namespace.c:delayed_mntput
  - fs/namespace.c:__cleanup_mnt
```
**Symbols:**

```
ffffffff812d3030-ffffffff812d30a2: cleanup_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cleanup_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:1090
Inline: False
Direct callers:
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:delayed_mntput
  - fs/namespace.c:__cleanup_mnt
```
**Symbols:**

```
ffffffff812f1260-ffffffff812f13b0: cleanup_mnt (STB_LOCAL)
ffffffff812f5fe1-ffffffff812f5ff4: cleanup_mnt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cleanup_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81302e00)
Location: fs/namespace.c:1090
Inline: False
Direct callers:
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:delayed_mntput
  - fs/namespace.c:__cleanup_mnt
```
**Symbols:**

```
ffffffff81302e00-ffffffff81302f60: cleanup_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cleanup_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133c830)
Location: fs/namespace.c:1106
Inline: False
Direct callers:
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:delayed_mntput
  - fs/namespace.c:__cleanup_mnt
```
**Symbols:**

```
ffffffff8133c830-ffffffff8133c9bc: cleanup_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cleanup_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813486f0)
Location: fs/namespace.c:1106
Inline: False
Direct callers:
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:delayed_mntput
  - fs/namespace.c:__cleanup_mnt
```
**Symbols:**

```
ffffffff813486f0-ffffffff8134887c: cleanup_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cleanup_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134eac0)
Location: fs/namespace.c:1116
Inline: False
Direct callers:
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:delayed_mntput
  - fs/namespace.c:__cleanup_mnt
```
**Symbols:**

```
ffffffff8134eac0-ffffffff8134ec50: cleanup_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cleanup_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139cb20)
Location: fs/namespace.c:1125
Inline: False
Direct callers:
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:delayed_mntput
  - fs/namespace.c:__cleanup_mnt
```
**Symbols:**

```
ffffffff8139cb20-ffffffff8139cce9: cleanup_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cleanup_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8141fa40)
Location: fs/namespace.c:1166
Inline: False
Direct callers:
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:delayed_mntput
  - fs/namespace.c:__cleanup_mnt
```
**Symbols:**

```
ffffffff8141fa40-ffffffff8141fc11: cleanup_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cleanup_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814abf80)
Location: fs/namespace.c:1271
Inline: False
Direct callers:
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:delayed_mntput
  - fs/namespace.c:__cleanup_mnt
```
**Symbols:**

```
ffffffff814abf80-ffffffff814ac0ea: cleanup_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cleanup_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e0d40)
Location: fs/namespace.c:1234
Inline: False
Direct callers:
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:delayed_mntput
  - fs/namespace.c:__cleanup_mnt
```
**Symbols:**

```
ffffffff814e0d40-ffffffff814e0ea8: cleanup_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cleanup_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81514e10)
Location: fs/namespace.c:1247
Inline: False
Direct callers:
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:delayed_mntput
  - fs/namespace.c:__cleanup_mnt
```
**Symbols:**

```
ffffffff81514e10-ffffffff81514f78: cleanup_mnt (STB_LOCAL)
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
void cleanup_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b61d8)
Location: fs/namespace.c:1090
Inline: False
Direct callers:
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:delayed_mntput
  - fs/namespace.c:__cleanup_mnt
```
**Symbols:**

```
ffff8000103b61d8-ffff8000103b6300: cleanup_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cleanup_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c059450c)
Location: fs/namespace.c:1090
Inline: False
Direct callers:
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:delayed_mntput
  - fs/namespace.c:__cleanup_mnt
```
**Symbols:**

```
c059450c-c0594644: cleanup_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cleanup_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b2740)
Location: fs/namespace.c:1090
Inline: False
Direct callers:
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:delayed_mntput
  - fs/namespace.c:__cleanup_mnt
```
**Symbols:**

```
c0000000004b2740-c0000000004b2924: cleanup_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cleanup_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe000278ee2)
Location: fs/namespace.c:1090
Inline: False
Direct callers:
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:delayed_mntput
  - fs/namespace.c:__cleanup_mnt
```
**Symbols:**

```
ffffffe000278ee2-ffffffe000278ff2: cleanup_mnt (STB_LOCAL)
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
void cleanup_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fb3e0)
Location: fs/namespace.c:1090
Inline: False
Direct callers:
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:delayed_mntput
  - fs/namespace.c:__cleanup_mnt
```
**Symbols:**

```
ffffffff812fb3e0-ffffffff812fb540: cleanup_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cleanup_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ec000)
Location: fs/namespace.c:1090
Inline: False
Direct callers:
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:delayed_mntput
  - fs/namespace.c:__cleanup_mnt
```
**Symbols:**

```
ffffffff812ec000-ffffffff812ec160: cleanup_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cleanup_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f91d0)
Location: fs/namespace.c:1090
Inline: False
Direct callers:
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:delayed_mntput
  - fs/namespace.c:__cleanup_mnt
```
**Symbols:**

```
ffffffff812f91d0-ffffffff812f9330: cleanup_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cleanup_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130a4f0)
Location: fs/namespace.c:1090
Inline: False
Direct callers:
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:delayed_mntput
  - fs/namespace.c:__cleanup_mnt
```
**Symbols:**

```
ffffffff8130a4f0-ffffffff8130a650: cleanup_mnt (STB_LOCAL)
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
