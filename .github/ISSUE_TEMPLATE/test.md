name: Bug report
description: Fill out this form to report a bug report.
labels:
  - bug
  - needs-triage

inputs:
  component:
    description: Component name or identifier
    required: true
    default: ""

title: "[Bug] ${{ inputs.component }}:"

body:
  - type: markdown
    attributes:
      value: |
        ## Description
        
        <!-- A clear and concise description of the bug -->
        
        ## Steps to reproduce
        
        1. 
        2. 
        3. 
        
        ## Expected behavior
        
        ## Actual behavior
        
        ## Environment
        
        - OS:
        - Browser / runtime:
        - Version:
        
        ## Additional context
        
        
