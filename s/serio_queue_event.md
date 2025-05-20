# Function: <code>serio_queue_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int serio_queue_event(void *object, struct module *owner, enum serio_event_type event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff816636d0)
Location: drivers/input/serio/serio.c:256
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:serio_reconnect
  - drivers/input/serio/serio.c:serio_resume
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/input/serio/serio.c:serio_interrupt
```
**Symbols:**

```
ffffffff816636d0-ffffffff81663803: serio_queue_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int serio_queue_event(void *object, struct module *owner, enum serio_event_type event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff816c38d0)
Location: drivers/input/serio/serio.c:256
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_resume
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:serio_reconnect
```
**Symbols:**

```
ffffffff816c38d0-ffffffff816c3a03: serio_queue_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int serio_queue_event(void *object, struct module *owner, enum serio_event_type event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff816f1890)
Location: drivers/input/serio/serio.c:256
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_resume
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:serio_reconnect
```
**Symbols:**

```
ffffffff816f1890-ffffffff816f19c3: serio_queue_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int serio_queue_event(void *object, struct module *owner, enum serio_event_type event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff81707100)
Location: drivers/input/serio/serio.c:256
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_resume
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:serio_reconnect
```
**Symbols:**

```
ffffffff81707100-ffffffff81707238: serio_queue_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int serio_queue_event(void *object, struct module *owner, enum serio_event_type event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff817782e0)
Location: drivers/input/serio/serio.c:256
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_resume
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:serio_reconnect
```
**Symbols:**

```
ffffffff817782e0-ffffffff81778418: serio_queue_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int serio_queue_event(void *object, struct module *owner, enum serio_event_type event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:256
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_resume
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:serio_reconnect
```
**Symbols:**

```
ffffffff817b8fe0-ffffffff817b90e6: serio_queue_event (STB_LOCAL)
ffffffff817ba1f5-ffffffff817ba231: serio_queue_event.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int serio_queue_event(void *object, struct module *owner, enum serio_event_type event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:252
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_resume
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:serio_reconnect
```
**Symbols:**

```
ffffffff817e03f0-ffffffff817e04f6: serio_queue_event (STB_LOCAL)
ffffffff817e161e-ffffffff817e165a: serio_queue_event.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int serio_queue_event(void *object, struct module *owner, enum serio_event_type event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:240
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_resume
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:serio_reconnect
```
**Symbols:**

```
ffffffff81820cb0-ffffffff81820da5: serio_queue_event (STB_LOCAL)
ffffffff81821e6e-ffffffff81821eaa: serio_queue_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int serio_queue_event(void *object, struct module *owner, enum serio_event_type event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:240
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_resume
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:serio_reconnect
```
**Symbols:**

```
ffffffff81852120-ffffffff81852215: serio_queue_event (STB_LOCAL)
ffffffff818532de-ffffffff8185331a: serio_queue_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int serio_queue_event(void *object, struct module *owner, enum serio_event_type event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:240
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_resume
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:serio_reconnect
```
**Symbols:**

```
ffffffff81923fd0-ffffffff819240c5: serio_queue_event (STB_LOCAL)
ffffffff81925459-ffffffff81925495: serio_queue_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int serio_queue_event(void *object, struct module *owner, enum serio_event_type event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:240
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_resume
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:serio_reconnect
```
**Symbols:**

```
ffffffff8192bd80-ffffffff8192be75: serio_queue_event (STB_LOCAL)
ffffffff81c22924-ffffffff81c22960: serio_queue_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int serio_queue_event(void *object, struct module *owner, enum serio_event_type event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:240
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_resume
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:serio_reconnect
```
**Symbols:**

```
ffffffff8190f290-ffffffff8190f385: serio_queue_event (STB_LOCAL)
ffffffff81c14b65-ffffffff81c14ba1: serio_queue_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int serio_queue_event(void *object, struct module *owner, enum serio_event_type event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:240
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_resume
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:serio_reconnect
```
**Symbols:**

```
ffffffff819b00d0-ffffffff819b01c5: serio_queue_event (STB_LOCAL)
ffffffff81d22164-ffffffff81d221a0: serio_queue_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int serio_queue_event(void *object, struct module *owner, enum serio_event_type event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:240
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_resume
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:serio_reconnect
```
**Symbols:**

```
ffffffff81b0ee10-ffffffff81b0ef0a: serio_queue_event (STB_LOCAL)
ffffffff81eedd34-ffffffff81eedd6e: serio_queue_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int serio_queue_event(void *object, struct module *owner, enum serio_event_type event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff81c9f110)
Location: drivers/input/serio/serio.c:237
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_resume
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:serio_reconnect
```
**Symbols:**

```
ffffffff81c9f110-ffffffff81c9f23a: serio_queue_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int serio_queue_event(void *object, struct module *owner, enum serio_event_type event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff81d06450)
Location: drivers/input/serio/serio.c:237
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_resume
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:serio_reconnect
```
**Symbols:**

```
ffffffff81d06450-ffffffff81d0657a: serio_queue_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int serio_queue_event(void *object, struct module *owner, enum serio_event_type event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff81dbc050)
Location: drivers/input/serio/serio.c:237
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_resume
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:serio_reconnect
```
**Symbols:**

```
ffffffff81dbc050-ffffffff81dbc1ad: serio_queue_event (STB_LOCAL)
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
int serio_queue_event(void *object, struct module *owner, enum serio_event_type event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffff800010a925f8)
Location: drivers/input/serio/serio.c:240
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_resume
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:serio_reconnect
```
**Symbols:**

```
ffff800010a925f8-ffff800010a927a0: serio_queue_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int serio_queue_event(void *object, struct module *owner, enum serio_event_type event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (c0b75aa4)
Location: drivers/input/serio/serio.c:240
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_resume
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:serio_reconnect
```
**Symbols:**

```
c0b75aa4-c0b75be0: serio_queue_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int serio_queue_event(void *object, struct module *owner, enum serio_event_type event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (c000000000b6dfa0)
Location: drivers/input/serio/serio.c:240
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_resume
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:serio_reconnect
```
**Symbols:**

```
c000000000b6dfa0-c000000000b6e160: serio_queue_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int serio_queue_event(void *object, struct module *owner, enum serio_event_type event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffe0006a4910)
Location: drivers/input/serio/serio.c:240
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_resume
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:serio_reconnect
```
**Symbols:**

```
ffffffe0006a4910-ffffffe0006a4a34: serio_queue_event (STB_LOCAL)
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
int serio_queue_event(void *object, struct module *owner, enum serio_event_type event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:240
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_resume
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:serio_reconnect
```
**Symbols:**

```
ffffffff81807200-ffffffff818072f5: serio_queue_event (STB_LOCAL)
ffffffff818083be-ffffffff818083fa: serio_queue_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int serio_queue_event(void *object, struct module *owner, enum serio_event_type event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:240
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_resume
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:serio_reconnect
```
**Symbols:**

```
ffffffff817ce910-ffffffff817cea05: serio_queue_event (STB_LOCAL)
ffffffff817cfa9e-ffffffff817cfada: serio_queue_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int serio_queue_event(void *object, struct module *owner, enum serio_event_type event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:240
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_resume
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:serio_reconnect
```
**Symbols:**

```
ffffffff818462b0-ffffffff818463a5: serio_queue_event (STB_LOCAL)
ffffffff8184746e-ffffffff818474aa: serio_queue_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int serio_queue_event(void *object, struct module *owner, enum serio_event_type event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:240
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_resume
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/serio/serio.c:serio_reconnect
```
**Symbols:**

```
ffffffff818618c0-ffffffff818619b5: serio_queue_event (STB_LOCAL)
ffffffff818626ab-ffffffff818626e7: serio_queue_event.cold (STB_LOCAL)
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
