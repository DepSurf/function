# Function: <code>t_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
void t_stop(struct seq_file *m, void *p);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114a9f0)
Location: kernel/trace/trace.c:3300
Inline: False
```
```
In kernel/trace/trace_printk.c (ffffffff811562f0)
Location: kernel/trace/trace_printk.c:327
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff81157db0)
Location: kernel/trace/trace_stack.c:320
Inline: False
```
```
In fs/proc/proc_tty.c (ffffffff81282030)
Location: fs/proc/proc_tty.c:115
Inline: False
```
**Symbols:**

```
ffffffff81142080-ffffffff81142092: t_stop (STB_LOCAL)
ffffffff8114a9f0-ffffffff8114aa02: t_stop (STB_LOCAL)
ffffffff811562f0-ffffffff81156302: t_stop (STB_LOCAL)
ffffffff81157db0-ffffffff81157de7: t_stop (STB_LOCAL)
ffffffff81160010-ffffffff81160022: t_stop (STB_LOCAL)
ffffffff81282030-ffffffff81282047: t_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
void t_stop(struct seq_file *m, void *p);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81148940)
Location: kernel/trace/ftrace.c:3237
Inline: False
```
```
In kernel/trace/trace.c (ffffffff81153410)
Location: kernel/trace/trace.c:3637
Inline: False
```
```
In kernel/trace/trace_printk.c (ffffffff8115f630)
Location: kernel/trace/trace_printk.c:335
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff81162630)
Location: kernel/trace/trace_stack.c:324
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:979
Inline: False
```
```
In fs/proc/proc_tty.c (ffffffff812af0e0)
Location: fs/proc/proc_tty.c:115
Inline: False
```
**Symbols:**

```
ffffffff81148940-ffffffff81148952: t_stop (STB_LOCAL)
ffffffff81153410-ffffffff81153422: t_stop (STB_LOCAL)
ffffffff8115f630-ffffffff8115f642: t_stop (STB_LOCAL)
ffffffff81162630-ffffffff81162667: t_stop (STB_LOCAL)
ffffffff8116a630-ffffffff8116a642: t_stop (STB_LOCAL)
ffffffff812af0e0-ffffffff812af0f7: t_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
void t_stop(struct seq_file *m, void *p);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811527f0)
Location: kernel/trace/ftrace.c:3255
Inline: False
```
```
In kernel/trace/trace.c (ffffffff8115d4d0)
Location: kernel/trace/trace.c:3861
Inline: False
```
```
In kernel/trace/trace_printk.c (ffffffff8116a090)
Location: kernel/trace/trace_printk.c:335
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff8116d970)
Location: kernel/trace/trace_stack.c:324
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:948
Inline: False
```
```
In fs/proc/proc_tty.c (ffffffff812c4ab0)
Location: fs/proc/proc_tty.c:115
Inline: False
```
**Symbols:**

```
ffffffff811527f0-ffffffff81152802: t_stop (STB_LOCAL)
ffffffff8115d4d0-ffffffff8115d4e2: t_stop (STB_LOCAL)
ffffffff8116a090-ffffffff8116a0a2: t_stop (STB_LOCAL)
ffffffff8116d970-ffffffff8116d9a7: t_stop (STB_LOCAL)
ffffffff81175920-ffffffff81175932: t_stop (STB_LOCAL)
ffffffff812c4ab0-ffffffff812c4ac7: t_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void t_stop(struct seq_file *m, void *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81154d60)
Location: kernel/trace/ftrace.c:3481
Inline: False
```
```
In kernel/trace/trace.c (ffffffff81160510)
Location: kernel/trace/trace.c:4091
Inline: False
```
```
In kernel/trace/trace_printk.c (ffffffff8116d040)
Location: kernel/trace/trace_printk.c:335
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff81170cf0)
Location: kernel/trace/trace_stack.c:327
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff81176740)
Location: kernel/trace/trace_events.c:988
Inline: True
```
```
In fs/proc/proc_tty.c (ffffffff812d1cd0)
Location: fs/proc/proc_tty.c:115
Inline: False
```
**Symbols:**

```
ffffffff81154d60-ffffffff81154d72: t_stop (STB_LOCAL)
ffffffff81160510-ffffffff81160522: t_stop (STB_LOCAL)
ffffffff8116d040-ffffffff8116d052: t_stop (STB_LOCAL)
ffffffff81170cf0-ffffffff81170d12: t_stop (STB_LOCAL)
ffffffff81176740-ffffffff81176752: t_stop (STB_LOCAL)
ffffffff812d1cd0-ffffffff812d1ce7: t_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void t_stop(struct seq_file *m, void *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81161590)
Location: kernel/trace/ftrace.c:3449
Inline: False
```
```
In kernel/trace/trace.c (ffffffff8116d5d0)
Location: kernel/trace/trace.c:4106
Inline: False
```
```
In kernel/trace/trace_printk.c (ffffffff8117a0f0)
Location: kernel/trace/trace_printk.c:335
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff8117deb0)
Location: kernel/trace/trace_stack.c:317
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff81183f00)
Location: kernel/trace/trace_events.c:988
Inline: True
```
```
In fs/proc/proc_tty.c (ffffffff812f64f0)
Location: fs/proc/proc_tty.c:117
Inline: False
```
**Symbols:**

```
ffffffff81161590-ffffffff811615a2: t_stop (STB_LOCAL)
ffffffff8116d5d0-ffffffff8116d5e2: t_stop (STB_LOCAL)
ffffffff8117a0f0-ffffffff8117a102: t_stop (STB_LOCAL)
ffffffff8117deb0-ffffffff8117ded2: t_stop (STB_LOCAL)
ffffffff81183f00-ffffffff81183f12: t_stop (STB_LOCAL)
ffffffff812f64f0-ffffffff812f6507: t_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
void t_stop(struct seq_file *m, void *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811704b0)
Location: kernel/trace/ftrace.c:3438
Inline: False
```
```
In kernel/trace/trace.c (ffffffff8117c750)
Location: kernel/trace/trace.c:4112
Inline: False
```
```
In kernel/trace/trace_printk.c (ffffffff811892b0)
Location: kernel/trace/trace_printk.c:335
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff8118d080)
Location: kernel/trace/trace_stack.c:317
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff81193040)
Location: kernel/trace/trace_events.c:986
Inline: True
```
```
In fs/proc/proc_tty.c (ffffffff813239b0)
Location: fs/proc/proc_tty.c:117
Inline: False
```
**Symbols:**

```
ffffffff811704b0-ffffffff811704c2: t_stop (STB_LOCAL)
ffffffff8117c750-ffffffff8117c762: t_stop (STB_LOCAL)
ffffffff811892b0-ffffffff811892c2: t_stop (STB_LOCAL)
ffffffff8118d080-ffffffff8118d0a2: t_stop (STB_LOCAL)
ffffffff81193040-ffffffff81193052: t_stop (STB_LOCAL)
ffffffff813239b0-ffffffff813239c7: t_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
void t_stop(struct seq_file *m, void *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8117dea0)
Location: kernel/trace/ftrace.c:3397
Inline: False
```
```
In kernel/trace/trace.c (ffffffff81189f50)
Location: kernel/trace/trace.c:4116
Inline: False
```
```
In kernel/trace/trace_printk.c (ffffffff81196b60)
Location: kernel/trace/trace_printk.c:336
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff8119aa00)
Location: kernel/trace/trace_stack.c:317
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff811a11b0)
Location: kernel/trace/trace_events.c:987
Inline: True
```
```
In fs/proc/proc_tty.c (ffffffff8133ab00)
Location: fs/proc/proc_tty.c:117
Inline: False
```
**Symbols:**

```
ffffffff8117dea0-ffffffff8117deb2: t_stop (STB_LOCAL)
ffffffff81189f50-ffffffff81189f62: t_stop (STB_LOCAL)
ffffffff81196b60-ffffffff81196b72: t_stop (STB_LOCAL)
ffffffff8119aa00-ffffffff8119aa22: t_stop (STB_LOCAL)
ffffffff811a11b0-ffffffff811a11c2: t_stop (STB_LOCAL)
ffffffff8133ab00-ffffffff8133ab17: t_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
void t_stop(struct seq_file *m, void *p);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118af40)
Location: kernel/trace/ftrace.c:3403
Inline: False
```
```
In kernel/trace/trace.c (ffffffff81197430)
Location: kernel/trace/trace.c:4321
Inline: False
```
```
In kernel/trace/trace_printk.c (ffffffff811a4a10)
Location: kernel/trace/trace_printk.c:336
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff811a85e0)
Location: kernel/trace/trace_stack.c:291
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff811af150)
Location: kernel/trace/trace_events.c:980
Inline: False
```
```
In fs/proc/proc_tty.c (ffffffff81362cb0)
Location: fs/proc/proc_tty.c:117
Inline: False
```
**Symbols:**

```
ffffffff8118af40-ffffffff8118af52: t_stop (STB_LOCAL)
ffffffff81197430-ffffffff81197442: t_stop (STB_LOCAL)
ffffffff811a4a10-ffffffff811a4a22: t_stop (STB_LOCAL)
ffffffff811a85e0-ffffffff811a8602: t_stop (STB_LOCAL)
ffffffff811af150-ffffffff811af162: t_stop (STB_LOCAL)
ffffffff81362cb0-ffffffff81362cc7: t_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
void t_stop(struct seq_file *m, void *p);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81196e30)
Location: kernel/trace/ftrace.c:3404
Inline: False
```
```
In kernel/trace/trace.c (ffffffff811a2df0)
Location: kernel/trace/trace.c:4350
Inline: False
```
```
In kernel/trace/trace_printk.c (ffffffff811b0210)
Location: kernel/trace/trace_printk.c:337
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff811b3df0)
Location: kernel/trace/trace_stack.c:409
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff811babb0)
Location: kernel/trace/trace_events.c:981
Inline: False
```
```
In fs/proc/proc_tty.c (ffffffff8137af10)
Location: fs/proc/proc_tty.c:117
Inline: False
```
**Symbols:**

```
ffffffff81196e30-ffffffff81196e42: t_stop (STB_LOCAL)
ffffffff811a2df0-ffffffff811a2e02: t_stop (STB_LOCAL)
ffffffff811b0210-ffffffff811b0222: t_stop (STB_LOCAL)
ffffffff811b3df0-ffffffff811b3e12: t_stop (STB_LOCAL)
ffffffff811babb0-ffffffff811babc2: t_stop (STB_LOCAL)
ffffffff8137af10-ffffffff8137af27: t_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void t_stop(struct seq_file *m, void *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ac1e0)
Location: kernel/trace/ftrace.c:3523
Inline: False
```
```
In kernel/trace/trace.c (ffffffff811b9820)
Location: kernel/trace/trace.c:4537
Inline: False
```
```
In kernel/trace/trace_printk.c (ffffffff811c83b0)
Location: kernel/trace/trace_printk.c:337
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff811ccb50)
Location: kernel/trace/trace_stack.c:409
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff811d3430)
Location: kernel/trace/trace_events.c:1055
Inline: True
```
```
In fs/proc/proc_tty.c (ffffffff813c4280)
Location: fs/proc/proc_tty.c:117
Inline: False
```
**Symbols:**

```
ffffffff811ac1e0-ffffffff811ac1f2: t_stop (STB_LOCAL)
ffffffff811b9820-ffffffff811b9832: t_stop (STB_LOCAL)
ffffffff811c83b0-ffffffff811c83c2: t_stop (STB_LOCAL)
ffffffff811ccb50-ffffffff811ccb72: t_stop (STB_LOCAL)
ffffffff811d3430-ffffffff811d3442: t_stop (STB_LOCAL)
ffffffff813c4280-ffffffff813c4297: t_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
void t_stop(struct seq_file *m, void *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811a9a70)
Location: kernel/trace/ftrace.c:3601
Inline: False
```
```
In kernel/trace/trace.c (ffffffff811b72f0)
Location: kernel/trace/trace.c:4605
Inline: False
```
```
In kernel/trace/trace_printk.c (ffffffff811c5aa0)
Location: kernel/trace/trace_printk.c:337
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff811ca090)
Location: kernel/trace/trace_stack.c:408
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff811d0580)
Location: kernel/trace/trace_events.c:1056
Inline: True
```
```
In fs/proc/proc_tty.c (ffffffff813d61e0)
Location: fs/proc/proc_tty.c:117
Inline: False
```
**Symbols:**

```
ffffffff811a9a70-ffffffff811a9a82: t_stop (STB_LOCAL)
ffffffff811b72f0-ffffffff811b7302: t_stop (STB_LOCAL)
ffffffff811c5aa0-ffffffff811c5ab2: t_stop (STB_LOCAL)
ffffffff811ca090-ffffffff811ca0b2: t_stop (STB_LOCAL)
ffffffff811d0580-ffffffff811d0592: t_stop (STB_LOCAL)
ffffffff813d61e0-ffffffff813d61f7: t_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void t_stop(struct seq_file *m, void *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811aa630)
Location: kernel/trace/ftrace.c:3601
Inline: False
```
```
In kernel/trace/trace.c (ffffffff811b7e10)
Location: kernel/trace/trace.c:4943
Inline: False
```
```
In kernel/trace/trace_printk.c (ffffffff811c6c90)
Location: kernel/trace/trace_printk.c:348
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff811cb450)
Location: kernel/trace/trace_stack.c:408
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff811d1730)
Location: kernel/trace/trace_events.c:1263
Inline: True
```
```
In fs/proc/proc_tty.c (ffffffff813dd0e0)
Location: fs/proc/proc_tty.c:117
Inline: False
```
**Symbols:**

```
ffffffff811aa630-ffffffff811aa642: t_stop (STB_LOCAL)
ffffffff811b7e10-ffffffff811b7e22: t_stop (STB_LOCAL)
ffffffff811c6c90-ffffffff811c6ca2: t_stop (STB_LOCAL)
ffffffff811cb450-ffffffff811cb472: t_stop (STB_LOCAL)
ffffffff811d1730-ffffffff811d1742: t_stop (STB_LOCAL)
ffffffff813dd0e0-ffffffff813dd0f7: t_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void t_stop(struct seq_file *m, void *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811d4140)
Location: kernel/trace/ftrace.c:3602
Inline: False
```
```
In kernel/trace/trace.c (ffffffff811e20e0)
Location: kernel/trace/trace.c:5017
Inline: False
```
```
In kernel/trace/trace_printk.c (ffffffff811f2150)
Location: kernel/trace/trace_printk.c:348
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff811f78e0)
Location: kernel/trace/trace_stack.c:408
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff811fe490)
Location: kernel/trace/trace_events.c:1264
Inline: True
```
```
In fs/proc/proc_tty.c (ffffffff8142e7d0)
Location: fs/proc/proc_tty.c:117
Inline: False
```
**Symbols:**

```
ffffffff811d4140-ffffffff811d4152: t_stop (STB_LOCAL)
ffffffff811e20e0-ffffffff811e20f2: t_stop (STB_LOCAL)
ffffffff811f2150-ffffffff811f2162: t_stop (STB_LOCAL)
ffffffff811f78e0-ffffffff811f7902: t_stop (STB_LOCAL)
ffffffff811fe490-ffffffff811fe4a2: t_stop (STB_LOCAL)
ffffffff8142e7d0-ffffffff8142e7e7: t_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
void t_stop(struct seq_file *m, void *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81208d70)
Location: kernel/trace/ftrace.c:3614
Inline: False
```
```
In kernel/trace/trace.c (ffffffff81218ee0)
Location: kernel/trace/trace.c:5018
Inline: False
```
```
In kernel/trace/trace_printk.c (ffffffff8122ab90)
Location: kernel/trace/trace_printk.c:348
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff81231550)
Location: kernel/trace/trace_stack.c:408
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff81238e90)
Location: kernel/trace/trace_events.c:1284
Inline: True
```
```
In fs/proc/proc_tty.c (ffffffff814a82e0)
Location: fs/proc/proc_tty.c:117
Inline: False
```
**Symbols:**

```
ffffffff81208d70-ffffffff81208d88: t_stop (STB_LOCAL)
ffffffff81218ee0-ffffffff81218ef8: t_stop (STB_LOCAL)
ffffffff8122ab90-ffffffff8122aba8: t_stop (STB_LOCAL)
ffffffff81231550-ffffffff81231578: t_stop (STB_LOCAL)
ffffffff81238e90-ffffffff81238ea8: t_stop (STB_LOCAL)
ffffffff814a82e0-ffffffff814a82fd: t_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
void t_stop(struct seq_file *m, void *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81251340)
Location: kernel/trace/ftrace.c:3634
Inline: False
```
```
In kernel/trace/trace.c (ffffffff81262f30)
Location: kernel/trace/trace.c:5042
Inline: False
```
```
In kernel/trace/trace_printk.c (ffffffff81276480)
Location: kernel/trace/trace_printk.c:348
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff8127dae0)
Location: kernel/trace/trace_stack.c:408
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff81285e10)
Location: kernel/trace/trace_events.c:1299
Inline: True
```
```
In fs/proc/proc_tty.c (ffffffff8153dbe0)
Location: fs/proc/proc_tty.c:115
Inline: False
```
**Symbols:**

```
ffffffff81251340-ffffffff81251358: t_stop (STB_LOCAL)
ffffffff81262f30-ffffffff81262f48: t_stop (STB_LOCAL)
ffffffff81276480-ffffffff81276498: t_stop (STB_LOCAL)
ffffffff8127dae0-ffffffff8127db0e: t_stop (STB_LOCAL)
ffffffff81285e10-ffffffff81285e28: t_stop (STB_LOCAL)
ffffffff8153dbe0-ffffffff8153dbfd: t_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
void t_stop(struct seq_file *m, void *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812687c0)
Location: kernel/trace/ftrace.c:3726
Inline: False
```
```
In kernel/trace/trace.c (ffffffff81279f10)
Location: kernel/trace/trace.c:5146
Inline: False
```
```
In kernel/trace/trace_printk.c (ffffffff8128de40)
Location: kernel/trace/trace_printk.c:348
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff8129a560)
Location: kernel/trace/trace_stack.c:408
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff812a2ad0)
Location: kernel/trace/trace_events.c:1295
Inline: True
```
```
In fs/proc/proc_tty.c (ffffffff81575eb0)
Location: fs/proc/proc_tty.c:115
Inline: False
```
**Symbols:**

```
ffffffff812687c0-ffffffff812687d8: t_stop (STB_LOCAL)
ffffffff81279f10-ffffffff81279f28: t_stop (STB_LOCAL)
ffffffff8128de40-ffffffff8128de58: t_stop (STB_LOCAL)
ffffffff8129a560-ffffffff8129a58e: t_stop (STB_LOCAL)
ffffffff812a2ad0-ffffffff812a2ae8: t_stop (STB_LOCAL)
ffffffff81575eb0-ffffffff81575ecd: t_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void t_stop(struct seq_file *m, void *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81282a30)
Location: kernel/trace/ftrace.c:3692
Inline: False
```
```
In kernel/trace/trace.c (ffffffff812949f0)
Location: kernel/trace/trace.c:5164
Inline: False
```
```
In kernel/trace/trace_printk.c (ffffffff812a9290)
Location: kernel/trace/trace_printk.c:348
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff812b5b20)
Location: kernel/trace/trace_stack.c:408
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff812be4a0)
Location: kernel/trace/trace_events.c:1304
Inline: True
```
```
In fs/proc/proc_tty.c (ffffffff815ae800)
Location: fs/proc/proc_tty.c:115
Inline: False
```
**Symbols:**

```
ffffffff81282a30-ffffffff81282a48: t_stop (STB_LOCAL)
ffffffff812949f0-ffffffff81294a08: t_stop (STB_LOCAL)
ffffffff812a9290-ffffffff812a92a8: t_stop (STB_LOCAL)
ffffffff812b5b20-ffffffff812b5b4e: t_stop (STB_LOCAL)
ffffffff812be4a0-ffffffff812be4b8: t_stop (STB_LOCAL)
ffffffff815ae800-ffffffff815ae81d: t_stop (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
void t_stop(struct seq_file *m, void *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff80001020f298)
Location: kernel/trace/ftrace.c:3404
Inline: False
```
```
In kernel/trace/trace.c (ffff80001021e148)
Location: kernel/trace/trace.c:4350
Inline: False
```
```
In kernel/trace/trace_printk.c (ffff80001022d870)
Location: kernel/trace/trace_printk.c:337
Inline: False
```
```
In kernel/trace/trace_stack.c (ffff8000102322c0)
Location: kernel/trace/trace_stack.c:409
Inline: False
```
```
In kernel/trace/trace_events.c (ffff800010239218)
Location: kernel/trace/trace_events.c:981
Inline: True
```
```
In fs/proc/proc_tty.c (ffff800010447548)
Location: fs/proc/proc_tty.c:117
Inline: False
```
**Symbols:**

```
ffff80001020f298-ffff80001020f2b4: t_stop (STB_LOCAL)
ffff80001021e148-ffff80001021e164: t_stop (STB_LOCAL)
ffff80001022d870-ffff80001022d88c: t_stop (STB_LOCAL)
ffff8000102322c0-ffff8000102322fc: t_stop (STB_LOCAL)
ffff800010239218-ffff800010239238: t_stop (STB_LOCAL)
ffff800010447548-ffff80001044756c: t_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
void t_stop(struct seq_file *m, void *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c044e2b0)
Location: kernel/trace/ftrace.c:3404
Inline: False
```
```
In kernel/trace/trace.c (c045c064)
Location: kernel/trace/trace.c:4350
Inline: False
```
```
In kernel/trace/trace_printk.c (c046b010)
Location: kernel/trace/trace_printk.c:337
Inline: False
```
```
In kernel/trace/trace_stack.c (c046de8c)
Location: kernel/trace/trace_stack.c:409
Inline: False
```
```
In kernel/trace/trace_events.c (c0474e20)
Location: kernel/trace/trace_events.c:981
Inline: True
```
```
In fs/proc/proc_tty.c (c060c460)
Location: fs/proc/proc_tty.c:117
Inline: False
```
**Symbols:**

```
c044e2b0-c044e2cc: t_stop (STB_LOCAL)
c045c064-c045c080: t_stop (STB_LOCAL)
c046b010-c046b02c: t_stop (STB_LOCAL)
c046de8c-c046ded8: t_stop (STB_LOCAL)
c0474e20-c0474e3c: t_stop (STB_LOCAL)
c060c460-c060c484: t_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
void t_stop(struct seq_file *m, void *p);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c00000000028ded0)
Location: kernel/trace/ftrace.c:3404
Inline: False
```
```
In kernel/trace/trace.c (c0000000002a0f60)
Location: kernel/trace/trace.c:4350
Inline: False
```
```
In kernel/trace/trace_printk.c (c0000000002b65e0)
Location: kernel/trace/trace_printk.c:337
Inline: False
```
```
In kernel/trace/trace_stack.c (c0000000002bc950)
Location: kernel/trace/trace_stack.c:409
Inline: False
```
```
In kernel/trace/trace_events.c (c0000000002c66f0)
Location: kernel/trace/trace_events.c:981
Inline: False
```
```
In fs/proc/proc_tty.c (c00000000055d740)
Location: fs/proc/proc_tty.c:117
Inline: False
```
**Symbols:**

```
c00000000028ded0-c00000000028df04: t_stop (STB_LOCAL)
c0000000002a0f60-c0000000002a0f94: t_stop (STB_LOCAL)
c0000000002b65e0-c0000000002b6614: t_stop (STB_LOCAL)
c0000000002bc950-c0000000002bc9a8: t_stop (STB_LOCAL)
c0000000002c66f0-c0000000002c6724: t_stop (STB_LOCAL)
c00000000055d740-c00000000055d77c: t_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
void t_stop(struct seq_file *m, void *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe00016ffe8)
Location: kernel/trace/ftrace.c:3404
Inline: False
```
```
In kernel/trace/trace.c (ffffffe00017abf6)
Location: kernel/trace/trace.c:4350
Inline: False
```
```
In kernel/trace/trace_printk.c (ffffffe0001872be)
Location: kernel/trace/trace_printk.c:337
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffe000189afe)
Location: kernel/trace/trace_stack.c:409
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffe000190192)
Location: kernel/trace/trace_events.c:981
Inline: True
```
```
In fs/proc/proc_tty.c (ffffffe0002dd23e)
Location: fs/proc/proc_tty.c:117
Inline: False
```
**Symbols:**

```
ffffffe00016ffe8-ffffffe000170008: t_stop (STB_LOCAL)
ffffffe00017abf6-ffffffe00017ac16: t_stop (STB_LOCAL)
ffffffe0001872be-ffffffe0001872de: t_stop (STB_LOCAL)
ffffffe000189afe-ffffffe000189b3e: t_stop (STB_LOCAL)
ffffffe000190192-ffffffe0001901b2: t_stop (STB_LOCAL)
ffffffe0002dd23e-ffffffe0002dd268: t_stop (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
void t_stop(struct seq_file *m, void *p);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118f450)
Location: kernel/trace/ftrace.c:3404
Inline: False
```
```
In kernel/trace/trace.c (ffffffff8119b410)
Location: kernel/trace/trace.c:4350
Inline: False
```
```
In kernel/trace/trace_printk.c (ffffffff811a8830)
Location: kernel/trace/trace_printk.c:337
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff811ac410)
Location: kernel/trace/trace_stack.c:409
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff811b31d0)
Location: kernel/trace/trace_events.c:981
Inline: False
```
```
In fs/proc/proc_tty.c (ffffffff813734f0)
Location: fs/proc/proc_tty.c:117
Inline: False
```
**Symbols:**

```
ffffffff8118f450-ffffffff8118f462: t_stop (STB_LOCAL)
ffffffff8119b410-ffffffff8119b422: t_stop (STB_LOCAL)
ffffffff811a8830-ffffffff811a8842: t_stop (STB_LOCAL)
ffffffff811ac410-ffffffff811ac432: t_stop (STB_LOCAL)
ffffffff811b31d0-ffffffff811b31e2: t_stop (STB_LOCAL)
ffffffff813734f0-ffffffff81373507: t_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
void t_stop(struct seq_file *m, void *p);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81182590)
Location: kernel/trace/ftrace.c:3404
Inline: False
```
```
In kernel/trace/trace.c (ffffffff8118e490)
Location: kernel/trace/trace.c:4350
Inline: False
```
```
In kernel/trace/trace_printk.c (ffffffff8119b7b0)
Location: kernel/trace/trace_printk.c:337
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff8119f2e0)
Location: kernel/trace/trace_stack.c:409
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff811a5fd0)
Location: kernel/trace/trace_events.c:981
Inline: False
```
```
In fs/proc/proc_tty.c (ffffffff81363fc0)
Location: fs/proc/proc_tty.c:117
Inline: False
```
**Symbols:**

```
ffffffff81182590-ffffffff811825a2: t_stop (STB_LOCAL)
ffffffff8118e490-ffffffff8118e4a2: t_stop (STB_LOCAL)
ffffffff8119b7b0-ffffffff8119b7c2: t_stop (STB_LOCAL)
ffffffff8119f2e0-ffffffff8119f2fc: t_stop (STB_LOCAL)
ffffffff811a5fd0-ffffffff811a5fe2: t_stop (STB_LOCAL)
ffffffff81363fc0-ffffffff81363fd7: t_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
void t_stop(struct seq_file *m, void *p);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118d220)
Location: kernel/trace/ftrace.c:3404
Inline: False
```
```
In kernel/trace/trace.c (ffffffff811991e0)
Location: kernel/trace/trace.c:4350
Inline: False
```
```
In kernel/trace/trace_printk.c (ffffffff811a6600)
Location: kernel/trace/trace_printk.c:337
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff811aa1e0)
Location: kernel/trace/trace_stack.c:409
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff811b0fa0)
Location: kernel/trace/trace_events.c:981
Inline: False
```
```
In fs/proc/proc_tty.c (ffffffff81370fc0)
Location: fs/proc/proc_tty.c:117
Inline: False
```
**Symbols:**

```
ffffffff8118d220-ffffffff8118d232: t_stop (STB_LOCAL)
ffffffff811991e0-ffffffff811991f2: t_stop (STB_LOCAL)
ffffffff811a6600-ffffffff811a6612: t_stop (STB_LOCAL)
ffffffff811aa1e0-ffffffff811aa202: t_stop (STB_LOCAL)
ffffffff811b0fa0-ffffffff811b0fb2: t_stop (STB_LOCAL)
ffffffff81370fc0-ffffffff81370fd7: t_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
void t_stop(struct seq_file *m, void *p);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119ad90)
Location: kernel/trace/ftrace.c:3404
Inline: False
```
```
In kernel/trace/trace.c (ffffffff811a6e40)
Location: kernel/trace/trace.c:4350
Inline: False
```
```
In kernel/trace/trace_printk.c (ffffffff811b43a0)
Location: kernel/trace/trace_printk.c:337
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff811b8020)
Location: kernel/trace/trace_stack.c:409
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff811bf040)
Location: kernel/trace/trace_events.c:981
Inline: False
```
```
In fs/proc/proc_tty.c (ffffffff813849a0)
Location: fs/proc/proc_tty.c:117
Inline: False
```
**Symbols:**

```
ffffffff8119ad90-ffffffff8119ada2: t_stop (STB_LOCAL)
ffffffff811a6e40-ffffffff811a6e52: t_stop (STB_LOCAL)
ffffffff811b43a0-ffffffff811b43b2: t_stop (STB_LOCAL)
ffffffff811b8020-ffffffff811b8042: t_stop (STB_LOCAL)
ffffffff811bf040-ffffffff811bf052: t_stop (STB_LOCAL)
ffffffff813849a0-ffffffff813849b7: t_stop (STB_LOCAL)
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
