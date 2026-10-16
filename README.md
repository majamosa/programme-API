# programme-API
I DID USE app.MapOpenAI because when you use .net 8.0.0
i have a proble connecting my Api 
my localhost 7298 does not work well ("becuse of not using AI I USED PEOPLE ON YOUTUBE PEOPLE LINK "BROCODE")
Line 1: # CMCS - This is Title of your project
Line 2: Blank line
Line 3: This system lets lecturers submit claims
Line 4: Blank
Line 5: ## How to Run
Line 6: 1. Press F5 in Visual Studio
Line 7: 2. Go to https://localhost:7294/swagger
Line 8: 3. Go to https://localhost:7294/index.html
Line 9: Blank
Line 10: ## API Endpoints (Your OLD API)
Line 11: POST /api/Lecturer/register - to register
Line 12: POST /api/Claims - to submit claim
Line 13: GET /api/Lecturer - get all lecturers
Line 14: GET /api/Claims - get all claims
Line 15: PUT /api/Claims/1/verify - verify
Line 16: PUT /api/Claims/1/approve - approve
Line 17: Blank
Line 18: ## What is inside
Line 19: Models/Lecturer.cs - has FullName, Email
Line 20: Models/Claim.cs - has HoursWorked * HourlyRate = TotalAmount
Line 21: Controllers - has the logic
Line 22: wwwroot/index.html - simple UI (HTML+CSS+JS in one file)
Line 23: Blank
Line 24: ## Unit Test
Line 25: New PROJECT CMCS.Tests (not folder)
Line 26: 4 tests - all must be green
Line 27: Test -> Run All Tests
