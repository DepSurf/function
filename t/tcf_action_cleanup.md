# Function: <code>tcf_action_cleanup</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcf_action_cleanup(struct tc_action *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81901c50)
Location: net/sched/act_api.c:92
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff81901c50-ffffffff81901cd5: tcf_action_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcf_action_cleanup(struct tc_action *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81962dc0)
Location: net/sched/act_api.c:116
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff81962dc0-ffffffff81962e54: tcf_action_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcf_action_cleanup(struct tc_action *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81999920)
Location: net/sched/act_api.c:116
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff81999920-ffffffff819999b4: tcf_action_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcf_action_cleanup(struct tc_action *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a72be0)
Location: net/sched/act_api.c:116
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_idr_delete_index
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:__tcf_action_put
```
**Symbols:**

```
ffffffff81a72be0-ffffffff81a72c77: tcf_action_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcf_action_cleanup(struct tc_action *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a7b7a0)
Location: net/sched/act_api.c:132
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_idr_delete_index
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:__tcf_action_put
```
**Symbols:**

```
ffffffff81a7b7a0-ffffffff81a7b837: tcf_action_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcf_action_cleanup(struct tc_action *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a644b0)
Location: net/sched/act_api.c:132
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_delete
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:__tcf_action_put
```
**Symbols:**

```
ffffffff81a644b0-ffffffff81a64547: tcf_action_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcf_action_cleanup(struct tc_action *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81b1d8c0)
Location: net/sched/act_api.c:132
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:__tcf_action_put
```
**Symbols:**

```
ffffffff81b1d8c0-ffffffff81b1d957: tcf_action_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcf_action_cleanup(struct tc_action *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ca55d0)
Location: net/sched/act_api.c:369
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:__tcf_action_put
```
**Symbols:**

```
ffffffff81ca55d0-ffffffff81ca5677: tcf_action_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcf_action_cleanup(struct tc_action *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81e620d0)
Location: net/sched/act_api.c:370
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:__tcf_action_put
```
**Symbols:**

```
ffffffff81e620d0-ffffffff81e62177: tcf_action_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcf_action_cleanup(struct tc_action *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ebda20)
Location: net/sched/act_api.c:363
Inline: False
Direct callers:
  - net/sched/act_api.c:__tcf_action_put
```
**Symbols:**

```
ffffffff81ebda20-ffffffff81ebdac7: tcf_action_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcf_action_cleanup(struct tc_action *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81f80b10)
Location: net/sched/act_api.c:363
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_reoffload_cb
  - net/sched/act_api.c:__tcf_action_put
```
**Symbols:**

```
ffffffff81f80b10-ffffffff81f80bb7: tcf_action_cleanup (STB_LOCAL)
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
void tcf_action_cleanup(struct tc_action *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffff800010c46760)
Location: net/sched/act_api.c:116
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffff800010c46760-ffff800010c467dc: tcf_action_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcf_action_cleanup(struct tc_action *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c0d58194)
Location: net/sched/act_api.c:116
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
c0d58194-c0d5820c: tcf_action_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcf_action_cleanup(struct tc_action *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c000000000d42df0)
Location: net/sched/act_api.c:116
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
c000000000d42df0-c000000000d42ee8: tcf_action_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcf_action_cleanup(struct tc_action *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffe0007b48ba)
Location: net/sched/act_api.c:116
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:__tcf_action_put
```
**Symbols:**

```
ffffffe0007b48ba-ffffffe0007b494c: tcf_action_cleanup (STB_LOCAL)
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
void tcf_action_cleanup(struct tc_action *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81939790)
Location: net/sched/act_api.c:116
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff81939790-ffffffff81939824: tcf_action_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcf_action_cleanup(struct tc_action *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818f3290)
Location: net/sched/act_api.c:116
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff818f3290-ffffffff818f3324: tcf_action_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcf_action_cleanup(struct tc_action *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8198a920)
Location: net/sched/act_api.c:116
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff8198a920-ffffffff8198a9b4: tcf_action_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcf_action_cleanup(struct tc_action *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff819ad110)
Location: net/sched/act_api.c:116
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff819ad110-ffffffff819ad1a4: tcf_action_cleanup (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
