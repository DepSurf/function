# Function: <code>may_linkat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int may_linkat(struct path *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81216f50)
Location: fs/namei.c:962
Inline: False
Direct callers:
  - fs/namei.c:SyS_link
```
**Symbols:**

```
ffffffff81216f50-ffffffff81216fd5: may_linkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int may_linkat(struct path *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123ddf0)
Location: fs/namei.c:987
Inline: False
Direct callers:
  - fs/namei.c:SyS_link
```
**Symbols:**

```
ffffffff8123ddf0-ffffffff8123de75: may_linkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int may_linkat(struct path *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81250bd0)
Location: fs/namei.c:987
Inline: False
Direct callers:
  - fs/namei.c:SyS_link
```
**Symbols:**

```
ffffffff81250bd0-ffffffff81250c55: may_linkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int may_linkat(struct path *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125cd50)
Location: fs/namei.c:999
Inline: False
Direct callers:
  - fs/namei.c:SyS_link
```
**Symbols:**

```
ffffffff8125cd50-ffffffff8125cdd2: may_linkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int may_linkat(struct path *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8127f160)
Location: fs/namei.c:1000
Inline: False
Direct callers:
  - fs/namei.c:SyS_link
```
**Symbols:**

```
ffffffff8127f160-ffffffff8127f1e2: may_linkat (STB_LOCAL)
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
In fs/namei.c (ffffffff812adffb)
Location: fs/namei.c:985
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
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
In fs/namei.c (ffffffff812c310b)
Location: fs/namei.c:987
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
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
In fs/namei.c (ffffffff812df84c)
Location: fs/namei.c:985
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
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
In fs/namei.c (ffffffff812f135c)
Location: fs/namei.c:979
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff81325860)
Location: fs/namei.c:1027
Inline: True
Direct callers:
  - fs/namei.c:do_linkat
```
**Symbols:**

```
ffffffff81325860-ffffffff813258f9: may_linkat.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int may_linkat(struct path *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813333b0)
Location: fs/namei.c:1027
Inline: True
Direct callers:
  - fs/namei.c:do_linkat
  - fs/init.c:init_link
```
**Symbols:**

```
ffffffff813333b0-ffffffff8133344d: may_linkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int may_linkat(struct user_namespace *mnt_userns, struct path *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81339440)
Location: fs/namei.c:1101
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/init.c:init_link
```
**Symbols:**

```
ffffffff81339440-ffffffff813394f1: may_linkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int may_linkat(struct user_namespace *mnt_userns, struct path *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81386aa0)
Location: fs/namei.c:1129
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/init.c:init_link
```
**Symbols:**

```
ffffffff81386aa0-ffffffff81386b51: may_linkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int may_linkat(struct user_namespace *mnt_userns, struct path *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81407740)
Location: fs/namei.c:1173
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/init.c:init_link
```
**Symbols:**

```
ffffffff81407740-ffffffff8140787a: may_linkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int may_linkat(struct user_namespace *mnt_userns, const struct path *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81491ba0)
Location: fs/namei.c:1181
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/init.c:init_link
```
**Symbols:**

```
ffffffff81491ba0-ffffffff81491cda: may_linkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int may_linkat(struct mnt_idmap *idmap, const struct path *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c6c50)
Location: fs/namei.c:1184
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/init.c:init_link
```
**Symbols:**

```
ffffffff814c6c50-ffffffff814c6d19: may_linkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int may_linkat(struct mnt_idmap *idmap, const struct path *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f95a0)
Location: fs/namei.c:1187
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/init.c:init_link
```
**Symbols:**

```
ffffffff814f95a0-ffffffff814f9669: may_linkat (STB_GLOBAL)
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
In fs/namei.c (ffff80001039aac8)
Location: fs/namei.c:979
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
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
In fs/namei.c (c0580f3c)
Location: fs/namei.c:979
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
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
In fs/namei.c (c000000000495954)
Location: fs/namei.c:979
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
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
In fs/namei.c (ffffffe000267ffc)
Location: fs/namei.c:979
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
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
In fs/namei.c (ffffffff812e993c)
Location: fs/namei.c:979
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
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
In fs/namei.c (ffffffff812da57c)
Location: fs/namei.c:979
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
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
In fs/namei.c (ffffffff812e774c)
Location: fs/namei.c:979
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
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
In fs/namei.c (ffffffff812f86cc)
Location: fs/namei.c:979
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>link</code> ➡️ <code>mnt_userns, link</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path *link</code> ➡️ <code>const struct path *link</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap *idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
