# WorkflowManager
Processes related to the management of workflows

  1. Parse nextflow and wdl pipelines to extract common run commands.
  2. Store these run command components in importable modules and version.
  3. Link modules and create new pipelines. Redo common pipelines with imports.
  4. Create training database - why run commands should be used over others.
  5. Ui for building pipelines top down and bottom up. All modules which match input output pairs.
  6. Testing using test input and output files for regression testing.
  7. Transcoding wdl to nextflow.
  8. Git exporter for finding input pipelines and differences.. cannot expect to be versioned appropriately. These use main branch instead of version releases.
