# Function: <code>input_unregister_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void input_unregister_handler(struct input_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81667f70)
Location: drivers/input/input.c:2242
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_toggle_support
  - drivers/tty/serial/kgdboc.c:kgdboc_restore_input_helper
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/evdev.c:evdev_exit
  - net/rfkill/input.c:rfkill_handler_exit
```
**Symbols:**

```
ffffffff81667f70-ffffffff81668038: input_unregister_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void input_unregister_handler(struct input_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff816c7ce0)
Location: drivers/input/input.c:2241
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_toggle_support
  - drivers/tty/serial/kgdboc.c:kgdboc_restore_input_helper
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/evdev.c:evdev_exit
  - net/rfkill/input.c:rfkill_handler_exit
```
**Symbols:**

```
ffffffff816c7ce0-ffffffff816c7d9f: input_unregister_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void input_unregister_handler(struct input_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff816f5cd0)
Location: drivers/input/input.c:2241
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_toggle_support
  - drivers/tty/serial/kgdboc.c:kgdboc_restore_input_helper
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/evdev.c:evdev_exit
  - net/rfkill/input.c:rfkill_handler_exit
```
**Symbols:**

```
ffffffff816f5cd0-ffffffff816f5d8f: input_unregister_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void input_unregister_handler(struct input_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8170b830)
Location: drivers/input/input.c:2247
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_toggle_support
  - drivers/tty/serial/kgdboc.c:kgdboc_restore_input_helper
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/evdev.c:evdev_exit
  - net/rfkill/input.c:rfkill_handler_exit
```
**Symbols:**

```
ffffffff8170b830-ffffffff8170b8e0: input_unregister_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void input_unregister_handler(struct input_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8177c840)
Location: drivers/input/input.c:2240
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_toggle_support
  - drivers/tty/serial/kgdboc.c:kgdboc_restore_input_helper
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/evdev.c:evdev_exit
  - net/rfkill/input.c:rfkill_handler_exit
```
**Symbols:**

```
ffffffff8177c840-ffffffff8177c8f5: input_unregister_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void input_unregister_handler(struct input_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff817bd8e0)
Location: drivers/input/input.c:2247
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_toggle_support
  - drivers/tty/serial/kgdboc.c:kgdboc_restore_input_helper
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/evdev.c:evdev_exit
  - net/rfkill/input.c:rfkill_handler_exit
```
**Symbols:**

```
ffffffff817bd8e0-ffffffff817bd995: input_unregister_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void input_unregister_handler(struct input_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff817e4d40)
Location: drivers/input/input.c:2247
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_toggle_support
  - drivers/tty/serial/kgdboc.c:kgdboc_restore_input_helper
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/evdev.c:evdev_exit
  - net/rfkill/input.c:rfkill_handler_exit
```
**Symbols:**

```
ffffffff817e4d40-ffffffff817e4df5: input_unregister_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void input_unregister_handler(struct input_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:2243
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_toggle_support
  - drivers/tty/serial/kgdboc.c:kgdboc_restore_input_helper
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/evdev.c:evdev_exit
  - net/rfkill/input.c:rfkill_handler_exit
```
**Symbols:**

```
ffffffff81828007-ffffffff8182801a: input_unregister_handler.cold (STB_LOCAL)
ffffffff818257a0-ffffffff81825855: input_unregister_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void input_unregister_handler(struct input_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81856cd0)
Location: drivers/input/input.c:2319
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_toggle_support
  - drivers/tty/serial/kgdboc.c:kgdboc_restore_input_helper
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/evdev.c:evdev_exit
  - net/rfkill/input.c:rfkill_handler_exit
```
**Symbols:**

```
ffffffff81856cd0-ffffffff81856d85: input_unregister_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void input_unregister_handler(struct input_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81929f30)
Location: drivers/input/input.c:2317
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_restore_input_helper
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/evdev.c:evdev_exit
  - net/rfkill/input.c:rfkill_handler_exit
```
**Symbols:**

```
ffffffff81929f30-ffffffff81929fe5: input_unregister_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void input_unregister_handler(struct input_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff819314a0)
Location: drivers/input/input.c:2423
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_restore_input_helper
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/evdev.c:evdev_exit
  - net/rfkill/input.c:rfkill_handler_exit
```
**Symbols:**

```
ffffffff819314a0-ffffffff81931555: input_unregister_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void input_unregister_handler(struct input_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81914ae0)
Location: drivers/input/input.c:2423
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_restore_input_helper
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/evdev.c:evdev_exit
  - net/rfkill/input.c:rfkill_handler_exit
```
**Symbols:**

```
ffffffff81914ae0-ffffffff81914b95: input_unregister_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void input_unregister_handler(struct input_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff819b6c70)
Location: drivers/input/input.c:2429
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_restore_input_helper
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/evdev.c:evdev_exit
  - net/rfkill/input.c:rfkill_handler_exit
```
**Symbols:**

```
ffffffff819b6c70-ffffffff819b6d25: input_unregister_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void input_unregister_handler(struct input_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81b16700)
Location: drivers/input/input.c:2473
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_restore_input_helper
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/evdev.c:evdev_exit
  - net/rfkill/input.c:rfkill_handler_exit
```
**Symbols:**

```
ffffffff81b16700-ffffffff81b167c3: input_unregister_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void input_unregister_handler(struct input_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81ca7a60)
Location: drivers/input/input.c:2485
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_restore_input_helper
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/evdev.c:evdev_exit
  - net/rfkill/input.c:rfkill_handler_exit
```
**Symbols:**

```
ffffffff81ca7a60-ffffffff81ca7b23: input_unregister_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void input_unregister_handler(struct input_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81d0ef70)
Location: drivers/input/input.c:2484
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_restore_input_helper
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/evdev.c:evdev_exit
  - net/rfkill/input.c:rfkill_handler_exit
```
**Symbols:**

```
ffffffff81d0ef70-ffffffff81d0f033: input_unregister_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void input_unregister_handler(struct input_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81dc4c90)
Location: drivers/input/input.c:2484
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_restore_input_helper
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/evdev.c:evdev_exit
  - net/rfkill/input.c:rfkill_handler_exit
```
**Symbols:**

```
ffffffff81dc4c90-ffffffff81dc4d53: input_unregister_handler (STB_GLOBAL)
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
void input_unregister_handler(struct input_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffff800010a95ef0)
Location: drivers/input/input.c:2319
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_toggle_support
  - drivers/tty/serial/kgdboc.c:kgdboc_restore_input_helper
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/evdev.c:evdev_exit
  - net/rfkill/input.c:rfkill_handler_exit
```
**Symbols:**

```
ffff800010a95ef0-ffff800010a95fc0: input_unregister_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void input_unregister_handler(struct input_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (c0b78bbc)
Location: drivers/input/input.c:2319
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_toggle_support
  - drivers/tty/serial/kgdboc.c:kgdboc_restore_input_helper
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/evdev.c:evdev_exit
  - net/rfkill/input.c:rfkill_handler_exit
```
**Symbols:**

```
c0b78bbc-c0b78c94: input_unregister_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void input_unregister_handler(struct input_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (c000000000b75500)
Location: drivers/input/input.c:2319
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_toggle_support
  - drivers/tty/serial/kgdboc.c:kgdboc_restore_input_helper
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/evdev.c:evdev_exit
  - net/rfkill/input.c:rfkill_handler_exit
```
**Symbols:**

```
c000000000b75500-c000000000b75620: input_unregister_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void input_unregister_handler(struct input_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffe0006a79b8)
Location: drivers/input/input.c:2319
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_toggle_support
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/evdev.c:evdev_exit
  - net/rfkill/input.c:rfkill_handler_exit
```
**Symbols:**

```
ffffffe0006a79b8-ffffffe0006a7a74: input_unregister_handler (STB_GLOBAL)
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
void input_unregister_handler(struct input_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8180bce0)
Location: drivers/input/input.c:2319
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_toggle_support
  - drivers/tty/serial/kgdboc.c:kgdboc_restore_input_helper
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/evdev.c:evdev_exit
  - net/rfkill/input.c:rfkill_handler_exit
```
**Symbols:**

```
ffffffff8180bce0-ffffffff8180bd95: input_unregister_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void input_unregister_handler(struct input_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff817d3450)
Location: drivers/input/input.c:2319
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_toggle_support
  - drivers/tty/serial/kgdboc.c:kgdboc_restore_input_helper
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/evdev.c:evdev_exit
  - net/rfkill/input.c:rfkill_handler_exit
```
**Symbols:**

```
ffffffff817d3450-ffffffff817d3505: input_unregister_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void input_unregister_handler(struct input_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8184ae60)
Location: drivers/input/input.c:2319
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_toggle_support
  - drivers/tty/serial/kgdboc.c:kgdboc_restore_input_helper
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/evdev.c:evdev_exit
  - net/rfkill/input.c:rfkill_handler_exit
```
**Symbols:**

```
ffffffff8184ae60-ffffffff8184af15: input_unregister_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void input_unregister_handler(struct input_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff818660b0)
Location: drivers/input/input.c:2319
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_toggle_support
  - drivers/tty/serial/kgdboc.c:kgdboc_restore_input_helper
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/evdev.c:evdev_exit
  - net/rfkill/input.c:rfkill_handler_exit
```
**Symbols:**

```
ffffffff818660b0-ffffffff81866165: input_unregister_handler (STB_GLOBAL)
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
