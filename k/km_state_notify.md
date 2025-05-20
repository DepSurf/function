# Function: <code>km_state_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void km_state_notify(struct xfrm_state *x, const struct km_event *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff817b6dd0)
Location: net/xfrm/xfrm_state.c:1709
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
```
**Symbols:**

```
ffffffff817b6dd0-ffffffff817b6e18: km_state_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void km_state_notify(struct xfrm_state *x, const struct km_event *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81827114)
Location: net/xfrm/xfrm_state.c:1710
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
```
**Symbols:**

```
ffffffff81823e00-ffffffff81823e48: km_state_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void km_state_notify(struct xfrm_state *x, const struct km_event *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff818588f4)
Location: net/xfrm/xfrm_state.c:1739
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
```
**Symbols:**

```
ffffffff81855750-ffffffff81855798: km_state_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void km_state_notify(struct xfrm_state *x, const struct km_event *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff8187c702)
Location: net/xfrm/xfrm_state.c:1902
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
```
**Symbols:**

```
ffffffff818792e0-ffffffff81879328: km_state_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void km_state_notify(struct xfrm_state *x, const struct km_event *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff818fd452)
Location: net/xfrm/xfrm_state.c:1918
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
```
**Symbols:**

```
ffffffff818f9d10-ffffffff818f9d5b: km_state_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void km_state_notify(struct xfrm_state *x, const struct km_event *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81953d4a)
Location: net/xfrm/xfrm_state.c:1919
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
```
**Symbols:**

```
ffffffff81950950-ffffffff8195099b: km_state_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void km_state_notify(struct xfrm_state *x, const struct km_event *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81986b38)
Location: net/xfrm/xfrm_state.c:1953
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
```
**Symbols:**

```
ffffffff81983e90-ffffffff81983edb: km_state_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void km_state_notify(struct xfrm_state *x, const struct km_event *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff819f0905)
Location: net/xfrm/xfrm_state.c:2129
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
```
**Symbols:**

```
ffffffff819eda30-ffffffff819eda7b: km_state_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void km_state_notify(struct xfrm_state *x, const struct km_event *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81a277d5)
Location: net/xfrm/xfrm_state.c:2131
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
```
**Symbols:**

```
ffffffff81a248e0-ffffffff81a2492b: km_state_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void km_state_notify(struct xfrm_state *x, const struct km_event *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81b18a52)
Location: net/xfrm/xfrm_state.c:2134
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
```
**Symbols:**

```
ffffffff81b16620-ffffffff81b1666b: km_state_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void km_state_notify(struct xfrm_state *x, const struct km_event *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81b27692)
Location: net/xfrm/xfrm_state.c:2170
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
```
**Symbols:**

```
ffffffff81b24b30-ffffffff81b24b80: km_state_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void km_state_notify(struct xfrm_state *x, const struct km_event *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81b152b2)
Location: net/xfrm/xfrm_state.c:2169
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
```
**Symbols:**

```
ffffffff81b12750-ffffffff81b127a0: km_state_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void km_state_notify(struct xfrm_state *x, const struct km_event *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81bd9432)
Location: net/xfrm/xfrm_state.c:2211
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
```
**Symbols:**

```
ffffffff81bd6670-ffffffff81bd66c0: km_state_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void km_state_notify(struct xfrm_state *x, const struct km_event *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81d6fbf2)
Location: net/xfrm/xfrm_state.c:2213
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
```
**Symbols:**

```
ffffffff81d6ce80-ffffffff81d6cedf: km_state_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void km_state_notify(struct xfrm_state *x, const struct km_event *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81f3b3e8)
Location: net/xfrm/xfrm_state.c:2379
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
```
**Symbols:**

```
ffffffff81f382b0-ffffffff81f3830f: km_state_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void km_state_notify(struct xfrm_state *x, const struct km_event *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81f9ae08)
Location: net/xfrm/xfrm_state.c:2376
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
```
**Symbols:**

```
ffffffff81f97ca0-ffffffff81f97cff: km_state_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void km_state_notify(struct xfrm_state *x, const struct km_event *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff82068168)
Location: net/xfrm/xfrm_state.c:2376
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
```
**Symbols:**

```
ffffffff82065010-ffffffff8206506f: km_state_notify (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void km_state_notify(struct xfrm_state *x, const struct km_event *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffff800010ce69b8)
Location: net/xfrm/xfrm_state.c:2131
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
```
**Symbols:**

```
ffff800010ce1fb8-ffff800010ce2020: km_state_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void km_state_notify(struct xfrm_state *x, const struct km_event *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (c0debf24)
Location: net/xfrm/xfrm_state.c:2131
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
```
**Symbols:**

```
c0deae3c-c0deae94: km_state_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void km_state_notify(struct xfrm_state *x, const struct km_event *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (c000000000e08298)
Location: net/xfrm/xfrm_state.c:2131
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
```
**Symbols:**

```
c000000000e04650-c000000000e046f0: km_state_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void km_state_notify(struct xfrm_state *x, const struct km_event *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffe000832520)
Location: net/xfrm/xfrm_state.c:2131
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
```
**Symbols:**

```
ffffffe000830788-ffffffe0008307d6: km_state_notify (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void km_state_notify(struct xfrm_state *x, const struct km_event *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff819c6e65)
Location: net/xfrm/xfrm_state.c:2131
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
```
**Symbols:**

```
ffffffff819c3f70-ffffffff819c3fbb: km_state_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void km_state_notify(struct xfrm_state *x, const struct km_event *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81983c55)
Location: net/xfrm/xfrm_state.c:2131
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
```
**Symbols:**

```
ffffffff81980d60-ffffffff81980dab: km_state_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void km_state_notify(struct xfrm_state *x, const struct km_event *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81a318e5)
Location: net/xfrm/xfrm_state.c:2131
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
```
**Symbols:**

```
ffffffff81a2e9f0-ffffffff81a2ea3b: km_state_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void km_state_notify(struct xfrm_state *x, const struct km_event *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81a3a470)
Location: net/xfrm/xfrm_state.c:2131
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_notify
```
**Symbols:**

```
ffffffff81a3a470-ffffffff81a3a4c5: km_state_notify (STB_GLOBAL)
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
