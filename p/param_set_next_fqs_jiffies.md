# Function: <code>param_set_next_fqs_jiffies</code>

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
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int param_set_next_fqs_jiffies(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:455
Inline: False
```
**Symbols:**

```
ffffffff81110820-ffffffff811108a9: param_set_next_fqs_jiffies (STB_LOCAL)
ffffffff811145c5-ffffffff811145d5: param_set_next_fqs_jiffies.cold.73 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int param_set_next_fqs_jiffies(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:465
Inline: False
```
**Symbols:**

```
ffffffff8111a240-ffffffff8111a2c8: param_set_next_fqs_jiffies (STB_LOCAL)
ffffffff8111e5ed-ffffffff8111e5fd: param_set_next_fqs_jiffies.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int param_set_next_fqs_jiffies(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:472
Inline: False
```
**Symbols:**

```
ffffffff81126650-ffffffff811266d8: param_set_next_fqs_jiffies (STB_LOCAL)
ffffffff8112ab6d-ffffffff8112ab7d: param_set_next_fqs_jiffies.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int param_set_next_fqs_jiffies(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:531
Inline: False
```
**Symbols:**

```
ffffffff811343a0-ffffffff81134429: param_set_next_fqs_jiffies (STB_LOCAL)
ffffffff81138e92-ffffffff81138ea2: param_set_next_fqs_jiffies.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int param_set_next_fqs_jiffies(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:545
Inline: False
```
**Symbols:**

```
ffffffff8112fe40-ffffffff8112fec9: param_set_next_fqs_jiffies (STB_LOCAL)
ffffffff81be2871-ffffffff81be2881: param_set_next_fqs_jiffies.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int param_set_next_fqs_jiffies(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:551
Inline: False
```
**Symbols:**

```
ffffffff81130360-ffffffff811303e6: param_set_next_fqs_jiffies (STB_LOCAL)
ffffffff81bd4810-ffffffff81bd4820: param_set_next_fqs_jiffies.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int param_set_next_fqs_jiffies(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:526
Inline: False
```
**Symbols:**

```
ffffffff81151be0-ffffffff81151c66: param_set_next_fqs_jiffies (STB_LOCAL)
ffffffff81caec0f-ffffffff81caec1f: param_set_next_fqs_jiffies.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int param_set_next_fqs_jiffies(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:537
Inline: False
```
**Symbols:**

```
ffffffff8117a290-ffffffff8117a32a: param_set_next_fqs_jiffies (STB_LOCAL)
ffffffff81e5f6d5-ffffffff81e5f6e5: param_set_next_fqs_jiffies.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int param_set_next_fqs_jiffies(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b0810)
Location: kernel/rcu/tree.c:468
Inline: False
```
**Symbols:**

```
ffffffff811b0810-ffffffff811b089f: param_set_next_fqs_jiffies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int param_set_next_fqs_jiffies(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c27e0)
Location: kernel/rcu/tree.c:449
Inline: False
```
**Symbols:**

```
ffffffff811c27e0-ffffffff811c286f: param_set_next_fqs_jiffies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int param_set_next_fqs_jiffies(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811d2d50)
Location: kernel/rcu/tree.c:450
Inline: False
```
**Symbols:**

```
ffffffff811d2d50-ffffffff811d2ddf: param_set_next_fqs_jiffies (STB_LOCAL)
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
int param_set_next_fqs_jiffies(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018bf88)
Location: kernel/rcu/tree.c:472
Inline: False
```
**Symbols:**

```
ffff80001018bf88-ffff80001018c044: param_set_next_fqs_jiffies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int param_set_next_fqs_jiffies(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03dc218)
Location: kernel/rcu/tree.c:472
Inline: False
```
**Symbols:**

```
c03dc218-c03dc2cc: param_set_next_fqs_jiffies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int param_set_next_fqs_jiffies(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e9420)
Location: kernel/rcu/tree.c:472
Inline: False
```
**Symbols:**

```
c0000000001e9420-c0000000001e9500: param_set_next_fqs_jiffies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int param_set_next_fqs_jiffies(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe0001210d0)
Location: kernel/rcu/tree.c:472
Inline: False
```
**Symbols:**

```
ffffffe0001210d0-ffffffe000121156: param_set_next_fqs_jiffies (STB_LOCAL)
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
int param_set_next_fqs_jiffies(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:472
Inline: False
```
**Symbols:**

```
ffffffff8111ec30-ffffffff8111ecb8: param_set_next_fqs_jiffies (STB_LOCAL)
ffffffff8112314d-ffffffff8112315d: param_set_next_fqs_jiffies.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int param_set_next_fqs_jiffies(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:472
Inline: False
```
**Symbols:**

```
ffffffff8110fbf0-ffffffff8110fc78: param_set_next_fqs_jiffies (STB_LOCAL)
ffffffff81115b96-ffffffff81115ba6: param_set_next_fqs_jiffies.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int param_set_next_fqs_jiffies(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:472
Inline: False
```
**Symbols:**

```
ffffffff8111cb20-ffffffff8111cba8: param_set_next_fqs_jiffies (STB_LOCAL)
ffffffff8112103d-ffffffff8112104d: param_set_next_fqs_jiffies.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int param_set_next_fqs_jiffies(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:472
Inline: False
```
**Symbols:**

```
ffffffff811296a0-ffffffff81129728: param_set_next_fqs_jiffies (STB_LOCAL)
ffffffff8112d390-ffffffff8112d3a0: param_set_next_fqs_jiffies.cold (STB_LOCAL)
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
