# Function: <code>tick_setup_periodic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void tick_setup_periodic(struct clock_event_device *dev, int broadcast);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff810fc6f0)
Location: kernel/time/tick-common.c:144
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
**Symbols:**

```
ffffffff810fc6f0-ffffffff810fc772: tick_setup_periodic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void tick_setup_periodic(struct clock_event_device *dev, int broadcast);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81103a40)
Location: kernel/time/tick-common.c:144
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
ffffffff81103a40-ffffffff81103ac4: tick_setup_periodic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void tick_setup_periodic(struct clock_event_device *dev, int broadcast);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff8110b130)
Location: kernel/time/tick-common.c:144
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
ffffffff8110b130-ffffffff8110b1b1: tick_setup_periodic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tick_setup_periodic(struct clock_event_device *dev, int broadcast);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff8110d020)
Location: kernel/time/tick-common.c:144
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
ffffffff8110d020-ffffffff8110d0a1: tick_setup_periodic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tick_setup_periodic(struct clock_event_device *dev, int broadcast);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff811182a0)
Location: kernel/time/tick-common.c:144
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
ffffffff811182a0-ffffffff81118321: tick_setup_periodic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tick_setup_periodic(struct clock_event_device *dev, int broadcast);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81124e20)
Location: kernel/time/tick-common.c:144
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
ffffffff81124e20-ffffffff81124ea6: tick_setup_periodic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tick_setup_periodic(struct clock_event_device *dev, int broadcast);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81130520)
Location: kernel/time/tick-common.c:140
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
ffffffff81130520-ffffffff811305a6: tick_setup_periodic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tick_setup_periodic(struct clock_event_device *dev, int broadcast);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff8113b070)
Location: kernel/time/tick-common.c:148
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
ffffffff8113b070-ffffffff8113b0f5: tick_setup_periodic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tick_setup_periodic(struct clock_event_device *dev, int broadcast);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81146c80)
Location: kernel/time/tick-common.c:148
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
ffffffff81146c80-ffffffff81146d05: tick_setup_periodic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tick_setup_periodic(struct clock_event_device *dev, int broadcast);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81156b40)
Location: kernel/time/tick-common.c:151
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
ffffffff81156b40-ffffffff81156bc7: tick_setup_periodic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tick_setup_periodic(struct clock_event_device *dev, int broadcast);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81152c60)
Location: kernel/time/tick-common.c:152
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
ffffffff81152c60-ffffffff81152ce7: tick_setup_periodic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tick_setup_periodic(struct clock_event_device *dev, int broadcast);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81153f50)
Location: kernel/time/tick-common.c:152
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
ffffffff81153f50-ffffffff81153fd7: tick_setup_periodic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tick_setup_periodic(struct clock_event_device *dev, int broadcast);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81178670)
Location: kernel/time/tick-common.c:152
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
ffffffff81178670-ffffffff811786f7: tick_setup_periodic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tick_setup_periodic(struct clock_event_device *dev, int broadcast);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff811ad870)
Location: kernel/time/tick-common.c:152
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
ffffffff811ad870-ffffffff811ad90d: tick_setup_periodic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tick_setup_periodic(struct clock_event_device *dev, int broadcast);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff811ede60)
Location: kernel/time/tick-common.c:152
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
ffffffff811ede60-ffffffff811edefd: tick_setup_periodic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tick_setup_periodic(struct clock_event_device *dev, int broadcast);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81202590)
Location: kernel/time/tick-common.c:152
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
ffffffff81202590-ffffffff8120262d: tick_setup_periodic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tick_setup_periodic(struct clock_event_device *dev, int broadcast);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81218a80)
Location: kernel/time/tick-common.c:152
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
ffffffff81218a80-ffffffff81218b1d: tick_setup_periodic (STB_GLOBAL)
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
void tick_setup_periodic(struct clock_event_device *dev, int broadcast);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffff8000101b1a88)
Location: kernel/time/tick-common.c:148
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
ffff8000101b1a88-ffff8000101b1b54: tick_setup_periodic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tick_setup_periodic(struct clock_event_device *dev, int broadcast);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (c03fc298)
Location: kernel/time/tick-common.c:148
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
c03fc298-c03fc398: tick_setup_periodic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tick_setup_periodic(struct clock_event_device *dev, int broadcast);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (c000000000216c40)
Location: kernel/time/tick-common.c:148
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
c000000000216c40-c000000000216d5c: tick_setup_periodic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tick_setup_periodic(struct clock_event_device *dev, int broadcast);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffe00013a2d6)
Location: kernel/time/tick-common.c:148
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
```
**Symbols:**

```
ffffffe00013a2d6-ffffffe00013a38e: tick_setup_periodic (STB_GLOBAL)
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
void tick_setup_periodic(struct clock_event_device *dev, int broadcast);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff8113f430)
Location: kernel/time/tick-common.c:148
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
ffffffff8113f430-ffffffff8113f4b5: tick_setup_periodic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tick_setup_periodic(struct clock_event_device *dev, int broadcast);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81131f60)
Location: kernel/time/tick-common.c:148
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
ffffffff81131f60-ffffffff81131fe5: tick_setup_periodic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tick_setup_periodic(struct clock_event_device *dev, int broadcast);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff8113d150)
Location: kernel/time/tick-common.c:148
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
ffffffff8113d150-ffffffff8113d1d5: tick_setup_periodic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tick_setup_periodic(struct clock_event_device *dev, int broadcast);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81149c40)
Location: kernel/time/tick-common.c:148
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
ffffffff81149c40-ffffffff81149cc5: tick_setup_periodic (STB_GLOBAL)
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
