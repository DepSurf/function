# Function: <code>reverse_path_check_proc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int reverse_path_check_proc(void *priv, void *cookie, int call_nests);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81254ce0)
Location: fs/eventpoll.c:1162
Inline: False
```
**Symbols:**

```
ffffffff81254ce0-ffffffff81254dba: reverse_path_check_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int reverse_path_check_proc(void *priv, void *cookie, int call_nests);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8127daa0)
Location: fs/eventpoll.c:1191
Inline: False
```
**Symbols:**

```
ffffffff8127daa0-ffffffff8127db80: reverse_path_check_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int reverse_path_check_proc(void *priv, void *cookie, int call_nests);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81291630)
Location: fs/eventpoll.c:1191
Inline: False
```
**Symbols:**

```
ffffffff81291630-ffffffff81291710: reverse_path_check_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int reverse_path_check_proc(void *priv, void *cookie, int call_nests);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8129e580)
Location: fs/eventpoll.c:1328
Inline: False
```
**Symbols:**

```
ffffffff8129e580-ffffffff8129e654: reverse_path_check_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int reverse_path_check_proc(void *priv, void *cookie, int call_nests);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812c12a0)
Location: fs/eventpoll.c:1310
Inline: False
```
**Symbols:**

```
ffffffff812c12a0-ffffffff812c136d: reverse_path_check_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int reverse_path_check_proc(void *priv, void *cookie, int call_nests);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (0)
Location: fs/eventpoll.c:1313
Inline: False
```
**Symbols:**

```
ffffffff812ea000-ffffffff812ea0c3: reverse_path_check_proc (STB_LOCAL)
ffffffff812ecb34-ffffffff812ecb45: reverse_path_check_proc.cold.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int reverse_path_check_proc(void *priv, void *cookie, int call_nests);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (0)
Location: fs/eventpoll.c:1317
Inline: False
```
**Symbols:**

```
ffffffff812feb80-ffffffff812fec43: reverse_path_check_proc (STB_LOCAL)
ffffffff81301540-ffffffff81301551: reverse_path_check_proc.cold.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int reverse_path_check_proc(void *priv, void *cookie, int call_nests);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (0)
Location: fs/eventpoll.c:1395
Inline: False
```
**Symbols:**

```
ffffffff8131fd50-ffffffff8131fe13: reverse_path_check_proc (STB_LOCAL)
ffffffff81322a86-ffffffff81322a97: reverse_path_check_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int reverse_path_check_proc(void *priv, void *cookie, int call_nests);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (0)
Location: fs/eventpoll.c:1395
Inline: False
```
**Symbols:**

```
ffffffff81332b00-ffffffff81332bc3: reverse_path_check_proc (STB_LOCAL)
ffffffff81335812-ffffffff81335823: reverse_path_check_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int reverse_path_check_proc(void *priv, void *cookie, int call_nests);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (0)
Location: fs/eventpoll.c:1388
Inline: False
```
**Symbols:**

```
ffffffff8136cdd0-ffffffff8136ce93: reverse_path_check_proc (STB_LOCAL)
ffffffff8136f3e3-ffffffff8136f3f4: reverse_path_check_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int reverse_path_check_proc(struct hlist_head *refs, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8137a280)
Location: fs/eventpoll.c:1310
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:reverse_path_check_proc
```
**Symbols:**

```
ffffffff8137a280-ffffffff8137a323: reverse_path_check_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int reverse_path_check_proc(struct hlist_head *refs, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81380ef0)
Location: fs/eventpoll.c:1316
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:reverse_path_check_proc
```
**Symbols:**

```
ffffffff81380ef0-ffffffff81380f93: reverse_path_check_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int reverse_path_check_proc(struct hlist_head *refs, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff813ce100)
Location: fs/eventpoll.c:1316
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:reverse_path_check_proc
```
**Symbols:**

```
ffffffff813ce100-ffffffff813ce1dd: reverse_path_check_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int reverse_path_check_proc(struct hlist_head *refs, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81457000)
Location: fs/eventpoll.c:1323
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:reverse_path_check_proc
```
**Symbols:**

```
ffffffff81457000-ffffffff814570f5: reverse_path_check_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int reverse_path_check_proc(struct hlist_head *refs, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff814e6210)
Location: fs/eventpoll.c:1325
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:reverse_path_check_proc
```
**Symbols:**

```
ffffffff814e6210-ffffffff814e6305: reverse_path_check_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int reverse_path_check_proc(struct hlist_head *refs, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8151cd70)
Location: fs/eventpoll.c:1364
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:reverse_path_check_proc
```
**Symbols:**

```
ffffffff8151cd70-ffffffff8151ce65: reverse_path_check_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int reverse_path_check_proc(struct hlist_head *refs, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81551350)
Location: fs/eventpoll.c:1355
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:reverse_path_check_proc
```
**Symbols:**

```
ffffffff81551350-ffffffff81551445: reverse_path_check_proc (STB_LOCAL)
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
int reverse_path_check_proc(void *priv, void *cookie, int call_nests);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffff8000103f1208)
Location: fs/eventpoll.c:1395
Inline: False
```
**Symbols:**

```
ffff8000103f1208-ffff8000103f1308: reverse_path_check_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int reverse_path_check_proc(void *priv, void *cookie, int call_nests);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (c05c6f2c)
Location: fs/eventpoll.c:1395
Inline: False
```
**Symbols:**

```
c05c6f2c-c05c701c: reverse_path_check_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int reverse_path_check_proc(void *priv, void *cookie, int call_nests);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (c0000000004f8c50)
Location: fs/eventpoll.c:1395
Inline: False
```
**Symbols:**

```
c0000000004f8c50-c0000000004f8df0: reverse_path_check_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int reverse_path_check_proc(void *priv, void *cookie, int call_nests);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffe0002a38c0)
Location: fs/eventpoll.c:1395
Inline: False
```
**Symbols:**

```
ffffffe0002a38c0-ffffffe0002a3994: reverse_path_check_proc (STB_LOCAL)
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
int reverse_path_check_proc(void *priv, void *cookie, int call_nests);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (0)
Location: fs/eventpoll.c:1395
Inline: False
```
**Symbols:**

```
ffffffff8132b0e0-ffffffff8132b1a3: reverse_path_check_proc (STB_LOCAL)
ffffffff8132ddf2-ffffffff8132de03: reverse_path_check_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int reverse_path_check_proc(void *priv, void *cookie, int call_nests);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (0)
Location: fs/eventpoll.c:1395
Inline: False
```
**Symbols:**

```
ffffffff8131c820-ffffffff8131c8e3: reverse_path_check_proc (STB_LOCAL)
ffffffff8131ea52-ffffffff8131ea63: reverse_path_check_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int reverse_path_check_proc(void *priv, void *cookie, int call_nests);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (0)
Location: fs/eventpoll.c:1395
Inline: False
```
**Symbols:**

```
ffffffff81328bb0-ffffffff81328c73: reverse_path_check_proc (STB_LOCAL)
ffffffff8132b8c2-ffffffff8132b8d3: reverse_path_check_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int reverse_path_check_proc(void *priv, void *cookie, int call_nests);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (0)
Location: fs/eventpoll.c:1395
Inline: False
```
**Symbols:**

```
ffffffff8133b590-ffffffff8133b664: reverse_path_check_proc (STB_LOCAL)
ffffffff8133e278-ffffffff8133e289: reverse_path_check_proc.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct hlist_head *refs</code>
</li>
<li>
<b>Param added. </b>
<code>int depth</code>
</li>
<li>
<b>Param removed. </b>
<code>void *priv</code>
</li>
<li>
<b>Param removed. </b>
<code>void *cookie</code>
</li>
<li>
<b>Param removed. </b>
<code>int call_nests</code>
</li>
</ul>
</details>
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
