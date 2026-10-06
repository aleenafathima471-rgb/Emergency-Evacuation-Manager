# Emergency Evacuation Manager
# Team Coding Contract

## Process Fields

- pid
- emergency_type
- arrival_time
- burst_time
- remaining_time
- priority
- resource
- state
- start_time
- completion_time
- waiting_time
- turnaround_time
- response_time

## Process States

- NEW
- READY
- RUNNING
- WAITING
- TERMINATED

## Scheduling Algorithms

- FCFS
- SJF
- RR
- PRIORITY

## Resources

- Ambulance
- Medical Team
- Fire Team
- Rescue Team

## API Endpoints

POST /api/processes
GET /api/processes
POST /api/simulation/run
GET /api/resources
GET /api/results
