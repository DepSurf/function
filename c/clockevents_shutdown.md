# Function: <code>clockevents_shutdown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void clockevents_shutdown(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff810fbf00)
Location: kernel/time/clockevents.c:179
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_suspend
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
**Symbols:**

```
ffffffff810fbf00-ffffffff810fbf28: clockevents_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void clockevents_shutdown(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8110351b)
Location: kernel/time/clockevents.c:179
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_suspend
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
**Symbols:**

```
ffffffff81103240-ffffffff81103268: clockevents_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void clockevents_shutdown(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8110ac0b)
Location: kernel/time/clockevents.c:179
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_suspend
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
**Symbols:**

```
ffffffff8110a930-ffffffff8110a958: clockevents_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void clockevents_shutdown(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8110cb1b)
Location: kernel/time/clockevents.c:179
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_suspend
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
**Symbols:**

```
ffffffff8110c870-ffffffff8110c898: clockevents_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void clockevents_shutdown(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81117d8b)
Location: kernel/time/clockevents.c:179
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_suspend
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
**Symbols:**

```
ffffffff81117ad0-ffffffff81117af8: clockevents_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void clockevents_shutdown(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8112486b)
Location: kernel/time/clockevents.c:179
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_suspend
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
**Symbols:**

```
ffffffff811245d0-ffffffff811245f8: clockevents_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void clockevents_shutdown(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8112ff6b)
Location: kernel/time/clockevents.c:171
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_suspend
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
**Symbols:**

```
ffffffff8112fcd0-ffffffff8112fcf8: clockevents_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void clockevents_shutdown(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8113aa0b)
Location: kernel/time/clockevents.c:171
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_suspend
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
**Symbols:**

```
ffffffff8113a780-ffffffff8113a7a8: clockevents_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void clockevents_shutdown(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8114668b)
Location: kernel/time/clockevents.c:171
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_suspend
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
**Symbols:**

```
ffffffff81146400-ffffffff81146428: clockevents_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void clockevents_shutdown(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff811564fc)
Location: kernel/time/clockevents.c:171
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_suspend
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
**Symbols:**

```
ffffffff81156240-ffffffff81156288: clockevents_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void clockevents_shutdown(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8115269c)
Location: kernel/time/clockevents.c:171
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_suspend
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
**Symbols:**

```
ffffffff811523e0-ffffffff81152428: clockevents_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void clockevents_shutdown(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81153aec)
Location: kernel/time/clockevents.c:171
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_suspend
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
**Symbols:**

```
ffffffff81153820-ffffffff81153868: clockevents_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void clockevents_shutdown(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff811781dc)
Location: kernel/time/clockevents.c:171
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_suspend
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
**Symbols:**

```
ffffffff81177ee0-ffffffff81177f28: clockevents_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void clockevents_shutdown(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff811ad35c)
Location: kernel/time/clockevents.c:171
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_suspend
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
**Symbols:**

```
ffffffff811ad030-ffffffff811ad080: clockevents_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void clockevents_shutdown(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff811ed8ac)
Location: kernel/time/clockevents.c:171
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_suspend
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
**Symbols:**

```
ffffffff811ed510-ffffffff811ed560: clockevents_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void clockevents_shutdown(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81201fdc)
Location: kernel/time/clockevents.c:171
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_suspend
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
**Symbols:**

```
ffffffff81201c30-ffffffff81201c80: clockevents_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void clockevents_shutdown(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8121847c)
Location: kernel/time/clockevents.c:171
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_suspend
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
**Symbols:**

```
ffffffff812180d0-ffffffff81218120: clockevents_shutdown (STB_GLOBAL)
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
void clockevents_shutdown(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffff8000101b1190)
Location: kernel/time/clockevents.c:171
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-common.c:tick_suspend_local
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
**Symbols:**

```
ffff8000101b0e58-ffff8000101b0e90: clockevents_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void clockevents_shutdown(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (c03fbc64)
Location: kernel/time/clockevents.c:171
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_suspend
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
**Symbols:**

```
c03fb8e4-c03fb914: clockevents_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void clockevents_shutdown(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (c000000000216188)
Location: kernel/time/clockevents.c:171
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_suspend
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
**Symbols:**

```
c000000000215c60-c000000000215cac: clockevents_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void clockevents_shutdown(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffe000139e68)
Location: kernel/time/clockevents.c:171
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-common.c:tick_suspend
```
**Symbols:**

```
ffffffe000139bda-ffffffe000139c0c: clockevents_shutdown (STB_GLOBAL)
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
void clockevents_shutdown(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8113ee3b)
Location: kernel/time/clockevents.c:171
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-common.c:tick_suspend
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
**Symbols:**

```
ffffffff8113ebb0-ffffffff8113ebd8: clockevents_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void clockevents_shutdown(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8113193b)
Location: kernel/time/clockevents.c:171
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_suspend
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
**Symbols:**

```
ffffffff811316d0-ffffffff811316f8: clockevents_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void clockevents_shutdown(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8113cb5b)
Location: kernel/time/clockevents.c:171
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_suspend
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
**Symbols:**

```
ffffffff8113c8d0-ffffffff8113c8f8: clockevents_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void clockevents_shutdown(struct clock_event_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8114964b)
Location: kernel/time/clockevents.c:171
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_suspend
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
**Symbols:**

```
ffffffff811493c0-ffffffff811493e8: clockevents_shutdown (STB_GLOBAL)
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
