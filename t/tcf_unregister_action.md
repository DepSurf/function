# Function: <code>tcf_unregister_action</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tcf_unregister_action(struct tc_action_ops *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81746ea0)
Location: net/sched/act_api.c:347
Inline: False
```
**Symbols:**

```
ffffffff81746ea0-ffffffff81746f3f: tcf_unregister_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tcf_unregister_action(struct tc_action_ops *act, struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817b40f0)
Location: net/sched/act_api.c:364
Inline: False
```
**Symbols:**

```
ffffffff817b40f0-ffffffff817b4184: tcf_unregister_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcf_unregister_action(struct tc_action_ops *act, struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817e3990)
Location: net/sched/act_api.c:372
Inline: False
```
**Symbols:**

```
ffffffff817e3990-ffffffff817e3a32: tcf_unregister_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int tcf_unregister_action(struct tc_action_ops *act, struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81803b60)
Location: net/sched/act_api.c:399
Inline: True
```
**Symbols:**

```
ffffffff81803b60-ffffffff81803bf0: tcf_unregister_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int tcf_unregister_action(struct tc_action_ops *act, struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81882050)
Location: net/sched/act_api.c:412
Inline: True
```
**Symbols:**

```
ffffffff81882050-ffffffff818820e0: tcf_unregister_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcf_unregister_action(struct tc_action_ops *act, struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818d5280)
Location: net/sched/act_api.c:432
Inline: False
```
**Symbols:**

```
ffffffff818d5280-ffffffff818d5310: tcf_unregister_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcf_unregister_action(struct tc_action_ops *act, struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81901ec0)
Location: net/sched/act_api.c:559
Inline: False
```
**Symbols:**

```
ffffffff81901ec0-ffffffff81901f50: tcf_unregister_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcf_unregister_action(struct tc_action_ops *act, struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81963040)
Location: net/sched/act_api.c:586
Inline: False
```
**Symbols:**

```
ffffffff81963040-ffffffff819630ce: tcf_unregister_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcf_unregister_action(struct tc_action_ops *act, struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81999bc0)
Location: net/sched/act_api.c:586
Inline: False
```
**Symbols:**

```
ffffffff81999bc0-ffffffff81999c4e: tcf_unregister_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcf_unregister_action(struct tc_action_ops *act, struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a724f0)
Location: net/sched/act_api.c:602
Inline: False
```
**Symbols:**

```
ffffffff81a724f0-ffffffff81a7257e: tcf_unregister_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcf_unregister_action(struct tc_action_ops *act, struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a7b0b0)
Location: net/sched/act_api.c:643
Inline: False
```
**Symbols:**

```
ffffffff81a7b0b0-ffffffff81a7b13e: tcf_unregister_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcf_unregister_action(struct tc_action_ops *act, struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a63e10)
Location: net/sched/act_api.c:656
Inline: False
```
**Symbols:**

```
ffffffff81a63e10-ffffffff81a63e9e: tcf_unregister_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcf_unregister_action(struct tc_action_ops *act, struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81b1d190)
Location: net/sched/act_api.c:656
Inline: False
```
**Symbols:**

```
ffffffff81b1d190-ffffffff81b1d21e: tcf_unregister_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int tcf_unregister_action(struct tc_action_ops *act, struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ca4810)
Location: net/sched/act_api.c:968
Inline: True
```
**Symbols:**

```
ffffffff81ca4810-ffffffff81ca48cd: tcf_unregister_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int tcf_unregister_action(struct tc_action_ops *act, struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81e61240)
Location: net/sched/act_api.c:994
Inline: True
```
**Symbols:**

```
ffffffff81e61240-ffffffff81e612fd: tcf_unregister_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int tcf_unregister_action(struct tc_action_ops *act, struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ebd290)
Location: net/sched/act_api.c:989
Inline: True
```
**Symbols:**

```
ffffffff81ebd290-ffffffff81ebd34d: tcf_unregister_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int tcf_unregister_action(struct tc_action_ops *act, struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81f80480)
Location: net/sched/act_api.c:1010
Inline: True
```
**Symbols:**

```
ffffffff81f80480-ffffffff81f8053d: tcf_unregister_action (STB_GLOBAL)
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
int tcf_unregister_action(struct tc_action_ops *act, struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffff800010c46e88)
Location: net/sched/act_api.c:586
Inline: False
```
**Symbols:**

```
ffff800010c46e88-ffff800010c46f90: tcf_unregister_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcf_unregister_action(struct tc_action_ops *act, struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c0d57980)
Location: net/sched/act_api.c:586
Inline: False
```
**Symbols:**

```
c0d57980-c0d57a40: tcf_unregister_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcf_unregister_action(struct tc_action_ops *act, struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c000000000d43260)
Location: net/sched/act_api.c:586
Inline: False
```
**Symbols:**

```
c000000000d43260-c000000000d43378: tcf_unregister_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcf_unregister_action(struct tc_action_ops *act, struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffe0007b4cbc)
Location: net/sched/act_api.c:586
Inline: False
```
**Symbols:**

```
ffffffe0007b4cbc-ffffffe0007b4d50: tcf_unregister_action (STB_GLOBAL)
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
int tcf_unregister_action(struct tc_action_ops *act, struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81939a30)
Location: net/sched/act_api.c:586
Inline: False
```
**Symbols:**

```
ffffffff81939a30-ffffffff81939abe: tcf_unregister_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcf_unregister_action(struct tc_action_ops *act, struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818f3530)
Location: net/sched/act_api.c:586
Inline: False
```
**Symbols:**

```
ffffffff818f3530-ffffffff818f35be: tcf_unregister_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcf_unregister_action(struct tc_action_ops *act, struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8198abc0)
Location: net/sched/act_api.c:586
Inline: False
```
**Symbols:**

```
ffffffff8198abc0-ffffffff8198ac4e: tcf_unregister_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcf_unregister_action(struct tc_action_ops *act, struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff819ad3b0)
Location: net/sched/act_api.c:586
Inline: False
```
**Symbols:**

```
ffffffff819ad3b0-ffffffff819ad448: tcf_unregister_action (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pernet_operations *ops</code>
</li>
</ul>
</details>
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
