# Manulife task guides

Personal working guides for Sahar's three Manulife tasks. Each guide covers what to do, what to ask (and whom), and what to learn. Issues live in `Sahar-Abdoli/PowerPlatformAgent`; the GitHub Project board is https://github.com/users/Sahar-Abdoli/projects/2/views/1.

| File | Task | Issue |
|---|---|---|
| `1037P-power-pages.html` | #1037P – Power Pages operationalization | [PowerPlatformAgent#1](https://github.com/Sahar-Abdoli/PowerPlatformAgent/issues/1) |
| `812-fabric-migration.html` | #812 – Power BI Premium → Fabric migration (target July 2027) | [PowerPlatformAgent#2](https://github.com/Sahar-Abdoli/PowerPlatformAgent/issues/2) |
| `1146-dataverse-capacity.html` | #1146 – Dataverse capacity cleanup, Cdn Seg Robotics Prod | [PowerPlatformAgent#3](https://github.com/Sahar-Abdoli/PowerPlatformAgent/issues/3) |

## How to update a guide (for Claude sessions)

The guides are living documents: when Sahar gives new context, edit the HTML in place and commit to `master`.

1. **Log the context first.** Add a dated entry to the guide's *Context log* section (`#context-log` in the Power Pages guide, `#context` in the other two). Newest entry on top, format: `<p><strong>YYYY-MM-DD</strong> — what was learned / decided, source (meeting, email, person).</p>`.
2. **Propagate it.** Update the affected sections: tick or rewrite steps in *What you should do*, remove or answer questions in *What you should ask* (keep the answer inline), and confirm or correct items in *Assumptions*.
3. **Bump the footer** `Last updated` date.
4. **Keep the shape.** Sections in order: Overview → Do → Ask → Learn → Risks → Assumptions → Context log. Self-contained HTML, inline CSS, colors as `:root` variables with a dark-mode block, no external scripts. Accents: Power Pages teal, Fabric indigo, Dataverse amber.
5. **Sources.** learn.microsoft.com was blocked from the session sandbox when these were written; links were confirmed via search results (Power Pages, Fabric) or the MicrosoftDocs source repos (Dataverse). Re-verify links when touching a section.

Do not modify the `PowerPlatformAgent` repo from guide updates unless Sahar asks; the guides only *suggest* PPOps extensions.
