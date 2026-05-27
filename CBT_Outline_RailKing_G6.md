# RailKing Gen6 CBT Outline (Draft v1)

## 1) Source Review Summary

Primary source set reviewed under:
- RailKing/Edited RK Part & Service Flash Drive Gen6 Operation Resources/

Key available documents:
- G6 Operator, Service and Parts Manual/Manuals/user.pdf
- G6 Operator, Service and Parts Manual/Manuals/warranty.pdf
- G6 Operator, Service and Parts Manual/Manuals/contacts.pdf
- G6 Operator, Service and Parts Manual/Manuals/form_parts_order.pdf
- G6 Operator, Service and Parts Manual/Manuals/form_equip_tech_support.pdf
- G6 Operator, Service and Parts Manual/Manuals/form_tech_manual_feedback.pdf
- G6 Operator, Service and Parts Manual/Manuals/form_sales_feedback.pdf
- G6 Operator, Service and Parts Manual/Manuals/RK22/RK22.pdf
- G6 Operator, Service and Parts Manual/Manuals/RK23/RK23.pdf
- G6 Operator, Service and Parts Manual/Manuals/RK24/RK24 Service Manual.pdf
- G6 Operator's Reference Guide/G6 Operator's Reference Guide.pdf

High-volume technical package (RK24):
- RK24 C5 Rev 1 Drawings: 58 PDF files
- RK24 C6 Rev 1 OEM Vendors: 31 PDF files

Observed structure notes:
- The folder named RK Part & Service Flash Drive Gen6 Operation Resources is duplicated inside the edited package. It appears to be a mirrored copy.
- The edited top-level package should be treated as the authoritative source to avoid duplicate references in the course build.

## 2) Recommended Course Strategy

Because the source includes both operator-level and deep service/OEM content, use a layered design:
- Core learner path: operators, lead operators, and field supervisors
- Advanced learner path: service technicians and support engineers

In this template system (linear sections), implement this as:
- Sections 1-5 = core path
- Section 6 = advanced service integration section
- Summary and final exam covering both, with exam weighting biased toward core operations

## 3) Course Skeleton (Template-Aligned)

Target package structure:
- Intro wrapper: CBT_Introduction.html
- Section wrappers: S1_Section1.html through S6_Section6.html
- Summary wrapper: SUM_CourseSum.html
- Final exam wrapper: EXAM_Final.html

Target pacing:
- Intro: 3-4 minutes
- Sections 1-5: 6-9 minutes each
- Section 6 (advanced): 8-10 minutes
- Summary: 3 minutes
- Final exam: 8-12 minutes
- Total: ~50-65 minutes

## 4) Proposed Learning Objectives

1. Identify the RailKing Gen6 document set and where to find operating, service, and support information.
2. Explain model family differences and common operating principles across RK22, RK23, and RK24.
3. Perform safe pre-operation checks and startup sequencing using the operator guidance.
4. Operate the machine through normal work cycles and monitor key indicators and limits.
5. Execute shutdown, post-operation checks, and escalation/support workflows.
6. Apply model-specific service references, drawings, and OEM documentation to troubleshoot and maintain RK24 systems.

## 5) Section Outline With Screen Plan

## Section 1: Documentation, Safety, and Support Workflow
Purpose:
- Orient learners to mandatory references, warranty boundaries, and support channels.

Suggested screens (6):
- S1-0_Section_Intro.html
- S1-1_Document_Library_Map.html
- S1-2_Safety_and_Responsibility.html
- S1-3_Warranty_and_Limits.html
- S1-4_Contacts_and_Support_Path.html
- S1-5_Forms_and_Data_Quality.html

Primary sources:
- user.pdf, warranty.pdf, contacts.pdf
- form_parts_order.pdf, form_equip_tech_support.pdf
- form_tech_manual_feedback.pdf, form_sales_feedback.pdf

Quiz focus:
- Which document to use for which scenario
- What data is required before opening support requests
- Warranty and escalation boundaries

## Section 2: Platform Overview (RK22, RK23, RK24)
Purpose:
- Build mental model of model variants and shared systems.

Suggested screens (5):
- S2-0_Section_Intro.html
- S2-1_Model_Family_Comparison.html
- S2-2_Common_Subsystems.html
- S2-3_Operator_Interface_Overview.html
- S2-4_When_to_Use_Model_Specific_Manuals.html

Primary sources:
- RK22.pdf, RK23.pdf, RK24 Service Manual.pdf
- G6 Operator's Reference Guide.pdf

Quiz focus:
- Distinguishing common vs model-specific guidance
- Correct manual selection for tasks

## Section 3: Pre-Operation and Startup
Purpose:
- Standardize pre-shift checks and startup process.

Suggested screens (6):
- S3-0_Section_Intro.html
- S3-1_PreOp_Inspection_Zones.html
- S3-2_Control_Panel_Readiness.html
- S3-3_Startup_Sequence.html
- S3-4_Abnormal_Conditions_HoldPoints.html
- S3-5_Startup_Confirmation_and_Recordkeeping.html

Primary sources:
- user.pdf
- G6 Operator's Reference Guide.pdf
- model manuals for model-specific startup notes

Quiz focus:
- Sequence order and decision points
- No-go conditions and safe escalation

## Section 4: Normal Operation and Performance Monitoring
Purpose:
- Teach repeatable operating practices and condition awareness.

Suggested screens (6):
- S4-0_Section_Intro.html
- S4-1_Operating_Cycle_Overview.html
- S4-2_Key_Indicators_and_Thresholds.html
- S4-3_Common_Adjustments_in_Service.html
- S4-4_Responding_to_Warnings.html
- S4-5_Handoff_Between_Operators.html

Primary sources:
- user.pdf
- G6 Operator's Reference Guide.pdf
- RK22/23/24 manuals as needed for thresholds and variants

Quiz focus:
- Interpreting indicators
- Correct response to common warning scenarios

## Section 5: Shutdown, Recovery, and Daily Service Interface
Purpose:
- Ensure controlled shutdown and clean handoff to service/support.

Suggested screens (5):
- S5-0_Section_Intro.html
- S5-1_Normal_Shutdown_Sequence.html
- S5-2_Securing_the_Unit.html
- S5-3_Post_Operation_Inspection.html
- S5-4_Service_Handoff_Packet.html

Primary sources:
- user.pdf
- contacts/forms PDFs
- model manuals for shutdown differences

Quiz focus:
- Correct shutdown order
- Required records and information for service handoff

## Section 6: Advanced Service Reference (RK24 Drawings + OEM Docs)
Purpose:
- Train service-level users to navigate and apply deep technical references.

Suggested screens (7):
- S6-0_Section_Intro.html
- S6-1_RK24_Drawing_Set_Navigation.html
- S6-2_OEM_Document_Bundles_by_Subsystem.html
- S6-3_Hydraulic_and_Pneumatic_Reference_Use.html
- S6-4_Controls_Display_and_Camera_References.html
- S6-5_Powertrain_Brake_and_Auxiliary_References.html
- S6-6_Case_Study_From_Symptom_to_Doc_to_Action.html

Primary sources:
- RK24 C5 Rev 1 Drawings (58 files)
- RK24 C6 Rev 1 OEM Vendors (31 files)
- RK24 Service Manual.pdf

Quiz focus:
- Selecting correct drawing/vendor manual for fault domains
- Cross-referencing service manual with OEM data sheets

## 6) Summary and Final Exam Design

Summary screens:
- SUM-1_Key_Takeaways.html
- SUM-2_Best_Practices.html

Exam recommendation:
- total_questions: 20
- pass_score: 16 (80%)
- question mix:
  - 12 questions from Sections 1-5 core operations
  - 8 questions from Section 6 advanced service references

## 7) Template Asset Mapping (Per Screen Type)

Use the CBT template layouts strategically:
- _TPL_content_screen.html:
  - General process and procedure slides (startup, shutdown, workflow)
- _TPL_comparison.html:
  - RK22 vs RK23 vs RK24 differences
- _TPL_process_layers.html:
  - Escalation path, startup gating, troubleshooting sequence
- _TPL_table_detail.html:
  - Fault code/reference table with click detail
- _TPL_diagram_cards.html:
  - System architecture + key component cards
- _TPL_stat_callouts.html:
  - KPI/limits and pass-fail threshold emphasis

## 8) Manifest Build Plan (What to Fill First)

1. Create _course_manifest.json in the course root.
2. Fill course and kla metadata.
3. Add intro with 6 objectives from this outline.
4. Add sections 1-6 with 5-7 screens each.
5. Add section quizzes (pick=4, pool target 7-8 questions each).
6. Add summary and final exam.
7. Build wrappers with:
   - C:\S2L_Dev\CBT-Template\_build_course.ps1 -CourseDir <course folder>

## 9) Open Content Decisions Needed

1. Primary audience priority:
   - Operator-only, or blended operator + service (current outline is blended)
2. Assessment policy:
   - Single final exam only, or section-gate strictness before next section
3. Model depth balance:
   - Equal RK22/RK23/RK24 coverage, or RK24-heavy coverage
4. Voiceover style:
   - Procedure-first (directive) or scenario-first (case-based)

## 10) Suggested Next Authoring Deliverables

1. Draft a filled _course_manifest.json with section/objective/question stubs.
2. Generate 2 pilot screens per section using the template HTMLs.
3. Run builder and perform first navigation/VO validation pass.
4. Expand each section question pool to target depth.
