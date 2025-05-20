# Function: <code>update_devfreq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int update_devfreq(struct devfreq *devfreq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff816ebd90)
Location: drivers/devfreq/devfreq.c:160
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/governor_userspace.c:store_freq
```
**Symbols:**

```
ffffffff816ebd90-ffffffff816ebe9e: update_devfreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int update_devfreq(struct devfreq *devfreq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81750a20)
Location: drivers/devfreq/devfreq.c:224
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/governor_userspace.c:store_freq
```
**Symbols:**

```
ffffffff81750a20-ffffffff81750c1c: update_devfreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int update_devfreq(struct devfreq *devfreq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8177c7a0)
Location: drivers/devfreq/devfreq.c:229
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/governor_userspace.c:store_freq
```
**Symbols:**

```
ffffffff8177c7a0-ffffffff8177c9a0: update_devfreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int update_devfreq(struct devfreq *devfreq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8179b360)
Location: drivers/devfreq/devfreq.c:227
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/governor_userspace.c:store_freq
```
**Symbols:**

```
ffffffff8179b360-ffffffff8179b56b: update_devfreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int update_devfreq(struct devfreq *devfreq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81811f80)
Location: drivers/devfreq/devfreq.c:256
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/governor_userspace.c:store_freq
```
**Symbols:**

```
ffffffff81811f80-ffffffff818121a3: update_devfreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int update_devfreq(struct devfreq *devfreq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8185be80)
Location: drivers/devfreq/devfreq.c:256
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/governor_userspace.c:store_freq
```
**Symbols:**

```
ffffffff8185be80-ffffffff8185c098: update_devfreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int update_devfreq(struct devfreq *devfreq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8187c640)
Location: drivers/devfreq/devfreq.c:335
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/governor_userspace.c:store_freq
```
**Symbols:**

```
ffffffff8187c640-ffffffff8187c721: update_devfreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int update_devfreq(struct devfreq *devfreq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff818c6a90)
Location: drivers/devfreq/devfreq.c:335
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/governor_userspace.c:store_freq
```
**Symbols:**

```
ffffffff818c6a90-ffffffff818c6b79: update_devfreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int update_devfreq(struct devfreq *devfreq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff818f7cd0)
Location: drivers/devfreq/devfreq.c:336
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/governor_userspace.c:store_freq
```
**Symbols:**

```
ffffffff818f7cd0-ffffffff818f7dbe: update_devfreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int update_devfreq(struct devfreq *devfreq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819cf8b0)
Location: drivers/devfreq/devfreq.c:389
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:qos_max_notifier_call
  - drivers/devfreq/devfreq.c:qos_min_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/governor_userspace.c:store_freq
```
**Symbols:**

```
ffffffff819cf8b0-ffffffff819cf952: update_devfreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int update_devfreq(struct devfreq *devfreq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819cf6a7)
Location: drivers/devfreq/devfreq.c:444
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:qos_max_notifier_call
  - drivers/devfreq/devfreq.c:qos_min_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
Direct callers:
  - drivers/devfreq/governor_userspace.c:store_freq
```
**Symbols:**

```
ffffffff819cf660-ffffffff819cf672: update_devfreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int update_devfreq(struct devfreq *devfreq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819b47d7)
Location: drivers/devfreq/devfreq.c:445
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:qos_max_notifier_call
  - drivers/devfreq/devfreq.c:qos_min_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
Direct callers:
  - drivers/devfreq/governor_userspace.c:store_freq
```
**Symbols:**

```
ffffffff819b4790-ffffffff819b47a2: update_devfreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int update_devfreq(struct devfreq *devfreq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81a63317)
Location: drivers/devfreq/devfreq.c:445
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:qos_max_notifier_call
  - drivers/devfreq/devfreq.c:qos_min_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
Direct callers:
  - drivers/devfreq/governor_userspace.c:set_freq_store
```
**Symbols:**

```
ffffffff81a632d0-ffffffff81a632e2: update_devfreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int update_devfreq(struct devfreq *devfreq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81bd2227)
Location: drivers/devfreq/devfreq.c:442
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:qos_max_notifier_call
  - drivers/devfreq/devfreq.c:qos_min_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
Direct callers:
  - drivers/devfreq/governor_userspace.c:set_freq_store
```
**Symbols:**

```
ffffffff81bd21e0-ffffffff81bd21fa: update_devfreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int update_devfreq(struct devfreq *devfreq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81d7de87)
Location: drivers/devfreq/devfreq.c:442
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:qos_max_notifier_call
  - drivers/devfreq/devfreq.c:qos_min_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
Direct callers:
  - drivers/devfreq/governor_userspace.c:set_freq_store
```
**Symbols:**

```
ffffffff81d7de30-ffffffff81d7de4a: update_devfreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int update_devfreq(struct devfreq *devfreq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81dec207)
Location: drivers/devfreq/devfreq.c:442
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:qos_max_notifier_call
  - drivers/devfreq/devfreq.c:qos_min_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
Direct callers:
  - drivers/devfreq/governor_userspace.c:set_freq_store
```
**Symbols:**

```
ffffffff81dec1b0-ffffffff81dec1ca: update_devfreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int update_devfreq(struct devfreq *devfreq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81ea27a7)
Location: drivers/devfreq/devfreq.c:442
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:qos_max_notifier_call
  - drivers/devfreq/devfreq.c:qos_min_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
Direct callers:
  - drivers/devfreq/governor_userspace.c:set_freq_store
```
**Symbols:**

```
ffffffff81ea25a0-ffffffff81ea25ba: update_devfreq (STB_GLOBAL)
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
int update_devfreq(struct devfreq *devfreq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffff800010b84068)
Location: drivers/devfreq/devfreq.c:336
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/governor_userspace.c:store_freq
```
**Symbols:**

```
ffff800010b84068-ffff800010b84154: update_devfreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int update_devfreq(struct devfreq *devfreq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (c0c67400)
Location: drivers/devfreq/devfreq.c:336
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/governor_userspace.c:store_freq
```
**Symbols:**

```
c0c67400-c0c674f8: update_devfreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int update_devfreq(struct devfreq *devfreq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (c000000000c619f0)
Location: drivers/devfreq/devfreq.c:336
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/governor_userspace.c:store_freq
```
**Symbols:**

```
c000000000c619f0-c000000000c61b54: update_devfreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int update_devfreq(struct devfreq *devfreq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffe00072d766)
Location: drivers/devfreq/devfreq.c:336
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/governor_userspace.c:store_freq
```
**Symbols:**

```
ffffffe00072d766-ffffffe00072d81c: update_devfreq (STB_GLOBAL)
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
int update_devfreq(struct devfreq *devfreq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81899000)
Location: drivers/devfreq/devfreq.c:336
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/governor_userspace.c:store_freq
```
**Symbols:**

```
ffffffff81899000-ffffffff818990ee: update_devfreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int update_devfreq(struct devfreq *devfreq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff818564d0)
Location: drivers/devfreq/devfreq.c:336
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/governor_userspace.c:store_freq
```
**Symbols:**

```
ffffffff818564d0-ffffffff818565be: update_devfreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int update_devfreq(struct devfreq *devfreq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff818e86f0)
Location: drivers/devfreq/devfreq.c:336
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/governor_userspace.c:store_freq
```
**Symbols:**

```
ffffffff818e86f0-ffffffff818e87de: update_devfreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int update_devfreq(struct devfreq *devfreq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81909760)
Location: drivers/devfreq/devfreq.c:336
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/governor_userspace.c:store_freq
```
**Symbols:**

```
ffffffff81909760-ffffffff8190984e: update_devfreq (STB_GLOBAL)
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
