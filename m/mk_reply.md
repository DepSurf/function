# Function: <code>mk_reply</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct taskstats *mk_reply(struct sk_buff *skb, int type, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8113e7a0)
Location: kernel/taskstats.c:364
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff8113e7a0-ffffffff8113e883: mk_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct taskstats *mk_reply(struct sk_buff *skb, int type, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81146dd0)
Location: kernel/taskstats.c:360
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
```
**Symbols:**

```
ffffffff81146dd0-ffffffff81146eb8: mk_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct taskstats *mk_reply(struct sk_buff *skb, int type, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81150c20)
Location: kernel/taskstats.c:359
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff81150c20-ffffffff81150d08: mk_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct taskstats *mk_reply(struct sk_buff *skb, int type, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81153220)
Location: kernel/taskstats.c:373
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff81153220-ffffffff811532f0: mk_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct taskstats *mk_reply(struct sk_buff *skb, int type, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8115fa20)
Location: kernel/taskstats.c:373
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff8115fa20-ffffffff8115faf0: mk_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct taskstats *mk_reply(struct sk_buff *skb, int type, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8116e970)
Location: kernel/taskstats.c:369
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff8116e970-ffffffff8116ea40: mk_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct taskstats *mk_reply(struct sk_buff *skb, int type, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8117c440)
Location: kernel/taskstats.c:369
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff8117c440-ffffffff8117c538: mk_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct taskstats *mk_reply(struct sk_buff *skb, int type, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/taskstats.c (0)
Location: kernel/taskstats.c:359
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff811892e0-ffffffff811893dd: mk_reply (STB_LOCAL)
ffffffff81189ba8-ffffffff81189bde: mk_reply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct taskstats *mk_reply(struct sk_buff *skb, int type, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81195220)
Location: kernel/taskstats.c:359
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff81195220-ffffffff8119531a: mk_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct taskstats *mk_reply(struct sk_buff *skb, int type, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811aa7b0)
Location: kernel/taskstats.c:359
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
```
**Symbols:**

```
ffffffff811aa7b0-ffffffff811aa8a8: mk_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct taskstats *mk_reply(struct sk_buff *skb, int type, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811a7d60)
Location: kernel/taskstats.c:355
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
```
**Symbols:**

```
ffffffff811a7d60-ffffffff811a7e58: mk_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct taskstats *mk_reply(struct sk_buff *skb, int type, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811a8680)
Location: kernel/taskstats.c:355
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
```
**Symbols:**

```
ffffffff811a8680-ffffffff811a8774: mk_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct taskstats *mk_reply(struct sk_buff *skb, int type, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811d2080)
Location: kernel/taskstats.c:355
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
```
**Symbols:**

```
ffffffff811d2080-ffffffff811d2174: mk_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct taskstats *mk_reply(struct sk_buff *skb, int type, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff812068c0)
Location: kernel/taskstats.c:377
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
```
**Symbols:**

```
ffffffff812068c0-ffffffff8120699c: mk_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct taskstats *mk_reply(struct sk_buff *skb, int type, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8124e930)
Location: kernel/taskstats.c:377
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
```
**Symbols:**

```
ffffffff8124e930-ffffffff8124ea0c: mk_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct taskstats *mk_reply(struct sk_buff *skb, int type, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81265ce0)
Location: kernel/taskstats.c:377
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
```
**Symbols:**

```
ffffffff81265ce0-ffffffff81265dbc: mk_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct taskstats *mk_reply(struct sk_buff *skb, int type, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8127fba0)
Location: kernel/taskstats.c:376
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
```
**Symbols:**

```
ffffffff8127fba0-ffffffff8127fc7c: mk_reply (STB_LOCAL)
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
struct taskstats *mk_reply(struct sk_buff *skb, int type, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffff80001020d4c8)
Location: kernel/taskstats.c:359
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
```
**Symbols:**

```
ffff80001020d4c8-ffff80001020d5f0: mk_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct taskstats *mk_reply(struct sk_buff *skb, int type, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (c044beb8)
Location: kernel/taskstats.c:359
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
```
**Symbols:**

```
c044beb8-c044bfd8: mk_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct taskstats *mk_reply(struct sk_buff *skb, int type, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (c00000000028b450)
Location: kernel/taskstats.c:359
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
```
**Symbols:**

```
c00000000028b450-c00000000028b5d0: mk_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct taskstats *mk_reply(struct sk_buff *skb, int type, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffe00016e59c)
Location: kernel/taskstats.c:359
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
```
**Symbols:**

```
ffffffe00016e59c-ffffffe00016e66a: mk_reply (STB_LOCAL)
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
struct taskstats *mk_reply(struct sk_buff *skb, int type, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8118d840)
Location: kernel/taskstats.c:359
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff8118d840-ffffffff8118d93a: mk_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct taskstats *mk_reply(struct sk_buff *skb, int type, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81180960)
Location: kernel/taskstats.c:359
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff81180960-ffffffff81180a5a: mk_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct taskstats *mk_reply(struct sk_buff *skb, int type, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8118b610)
Location: kernel/taskstats.c:359
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff8118b610-ffffffff8118b70a: mk_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct taskstats *mk_reply(struct sk_buff *skb, int type, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81198f80)
Location: kernel/taskstats.c:359
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff81198f80-ffffffff8119907a: mk_reply (STB_LOCAL)
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
