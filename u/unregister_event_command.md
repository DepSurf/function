# Function: <code>unregister_event_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff81f855b1)
Location: kernel/trace/trace_events_trigger.c:337
Inline: True
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
```
**Symbols:**

```
ffffffff81f855b1-ffffffff81f85629: unregister_event_command.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int unregister_event_command(struct event_command *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff81faebbc)
Location: kernel/trace/trace_events_trigger.c:350
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
```
**Symbols:**

```
ffffffff81faebbc-ffffffff81faec3b: unregister_event_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int unregister_event_command(struct event_command *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff81feb1e3)
Location: kernel/trace/trace_events_trigger.c:350
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
```
**Symbols:**

```
ffffffff81feb1e3-ffffffff81feb262: unregister_event_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int unregister_event_command(struct event_command *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff820cbbe5)
Location: kernel/trace/trace_events_trigger.c:351
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
```
**Symbols:**

```
ffffffff820cbbe5-ffffffff820cbc64: unregister_event_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int unregister_event_command(struct event_command *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff826d4254)
Location: kernel/trace/trace_events_trigger.c:351
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
```
**Symbols:**

```
ffffffff826d4254-ffffffff826d42d3: unregister_event_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int unregister_event_command(struct event_command *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff826fe9aa)
Location: kernel/trace/trace_events_trigger.c:350
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
```
**Symbols:**

```
ffffffff826fe9aa-ffffffff826fea29: unregister_event_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int unregister_event_command(struct event_command *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff828b58c4)
Location: kernel/trace/trace_events_trigger.c:339
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
```
**Symbols:**

```
ffffffff828b58c4-ffffffff828b5943: unregister_event_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int unregister_event_command(struct event_command *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff828ce833)
Location: kernel/trace/trace_events_trigger.c:339
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
```
**Symbols:**

```
ffffffff828ce833-ffffffff828ce8b2: unregister_event_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int unregister_event_command(struct event_command *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff828d6d85)
Location: kernel/trace/trace_events_trigger.c:346
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
```
**Symbols:**

```
ffffffff828d6d85-ffffffff828d6e04: unregister_event_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int unregister_event_command(struct event_command *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff82cf69af)
Location: kernel/trace/trace_events_trigger.c:352
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
```
**Symbols:**

```
ffffffff82cf69af-ffffffff82cf6a2e: unregister_event_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int unregister_event_command(struct event_command *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff82fe34a0)
Location: kernel/trace/trace_events_trigger.c:352
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
```
**Symbols:**

```
ffffffff82fe34a0-ffffffff82fe351f: unregister_event_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int unregister_event_command(struct event_command *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff831edc12)
Location: kernel/trace/trace_events_trigger.c:353
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
```
**Symbols:**

```
ffffffff831edc12-ffffffff831edc91: unregister_event_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int unregister_event_command(struct event_command *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff832d2889)
Location: kernel/trace/trace_events_trigger.c:365
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
```
**Symbols:**

```
ffffffff832d2889-ffffffff832d2908: unregister_event_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int unregister_event_command(struct event_command *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff83486cbc)
Location: kernel/trace/trace_events_trigger.c:379
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
```
**Symbols:**

```
ffffffff83486cbc-ffffffff83486d45: unregister_event_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int unregister_event_command(struct event_command *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff83eb6490)
Location: kernel/trace/trace_events_trigger.c:380
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
```
**Symbols:**

```
ffffffff83eb6490-ffffffff83eb652f: unregister_event_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int unregister_event_command(struct event_command *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff836db870)
Location: kernel/trace/trace_events_trigger.c:382
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
```
**Symbols:**

```
ffffffff836db870-ffffffff836db90f: unregister_event_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int unregister_event_command(struct event_command *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff8390de10)
Location: kernel/trace/trace_events_trigger.c:382
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
```
**Symbols:**

```
ffffffff8390de10-ffffffff8390deaf: unregister_event_command (STB_GLOBAL)
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
int unregister_event_command(struct event_command *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffff80001144f680)
Location: kernel/trace/trace_events_trigger.c:346
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
```
**Symbols:**

```
ffff80001144f680-ffff80001144f718: unregister_event_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int unregister_event_command(struct event_command *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (c1529f04)
Location: kernel/trace/trace_events_trigger.c:346
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
```
**Symbols:**

```
c1529f04-c1529f88: unregister_event_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int unregister_event_command(struct event_command *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (c000000001376770)
Location: kernel/trace/trace_events_trigger.c:346
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
```
**Symbols:**

```
c000000001376770-c000000001376850: unregister_event_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int unregister_event_command(struct event_command *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffe00000faa6)
Location: kernel/trace/trace_events_trigger.c:346
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
```
**Symbols:**

```
ffffffe00000faa6-ffffffe00000fb30: unregister_event_command (STB_GLOBAL)
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
int unregister_event_command(struct event_command *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff828bfc36)
Location: kernel/trace/trace_events_trigger.c:346
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
```
**Symbols:**

```
ffffffff828bfc36-ffffffff828bfcb5: unregister_event_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int unregister_event_command(struct event_command *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff828b82d6)
Location: kernel/trace/trace_events_trigger.c:346
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
```
**Symbols:**

```
ffffffff828b82d6-ffffffff828b8355: unregister_event_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int unregister_event_command(struct event_command *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff828d29b9)
Location: kernel/trace/trace_events_trigger.c:346
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
```
**Symbols:**

```
ffffffff828d29b9-ffffffff828d2a38: unregister_event_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int unregister_event_command(struct event_command *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff828d7dda)
Location: kernel/trace/trace_events_trigger.c:346
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_trigger.c:register_trigger_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
  - kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds
```
**Symbols:**

```
ffffffff828d7dda-ffffffff828d7e59: unregister_event_command (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
