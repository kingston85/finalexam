import React, { useState } from 'react';
import { Search, User, BookOpen, Award, Eye, EyeOff, Lock } from 'lucide-react';

const StudentDashboard = () => {
  const [studentId, setStudentId] = useState('');
  const [showScore, setShowScore] = useState(false);
  const [studentData, setStudentData] = useState(null);
  const [error, setError] = useState('');
  const [isLoading, setIsLoading] = useState(false);

  // Student data (in real app, this would come from a secure backend)
  const studentsData = [
    { id: '97908', name: 'Abraham S. Borbor', finalExam: 70, grade: 'B' },
    { id: '94884', name: 'Adah L. Dolo', finalExam: 75, grade: 'D' },
    { id: '96018', name: 'Agnes K. Tamba', finalExam: 0, grade: 'F' },
    { id: '98679', name: 'Aloysious K. Jimmy', finalExam: 65, grade: 'C' },
    { id: '91218', name: 'Antoinette C. Manneh', finalExam: 55, grade: 'D' },
    { id: '98173', name: 'Brette C. Carter', finalExam: 70, grade: 'D' },
    { id: '88378', name: 'Cleopatra D. Crawford', finalExam: 60, grade: 'C' },
    { id: '99313', name: 'Damazine Brown', finalExam: 65, grade: 'D' },
    { id: '98163', name: 'Diamond Tolah', finalExam: 90, grade: 'B' },
    { id: '96498', name: 'Emmanuelle Clark Zion', finalExam: 90, grade: 'C' },
    { id: '96949', name: 'Emmanuel Zawolo', finalExam: 60, grade: 'C' },
    { id: '95750', name: 'Esther T. Kiazolu', finalExam: 85, grade: 'B' },
    { id: '98777', name: 'Gbolu T. Yorkor', finalExam: 55, grade: 'C' },
    { id: '99668', name: 'Harris B. Mcgill', finalExam: 60, grade: 'C' },
    { id: '96945', name: 'Helen Gaymore', finalExam: 65, grade: 'C' },
    { id: '95097', name: 'Helena A. Kollie', finalExam: 80, grade: 'C' },
    { id: '95898', name: 'Jefferson K. Gblinwon', finalExam: 60, grade: 'C' },
    { id: '94147', name: 'Jeremiah Tamba', finalExam: 55, grade: 'F' },
    { id: '97082', name: 'Josephine M. Mulbah', finalExam: 80, grade: 'D' },
    { id: '96875', name: 'Julie T. Nadoue', finalExam: 80, grade: 'C' },
    { id: '98896', name: 'Malaway Bunadin', finalExam: 90, grade: 'C' },
    { id: '95536', name: 'Maraline Flomo', finalExam: 60, grade: 'D' },
    { id: '95646', name: 'Mark Gehmie', finalExam: 80, grade: 'D' },
    { id: '90223', name: 'Memee R. Gliklay', finalExam: 70, grade: 'C' },
    { id: '97099', name: 'Mercy Cyrus', finalExam: 55, grade: 'C' },
    { id: '97448', name: 'Mercy Y. Sokpah', finalExam: 65, grade: 'C' },
    { id: '96571', name: 'Mohammed Swaray', finalExam: 60, grade: 'C' },
    { id: '79019', name: 'Musu M. Yarkpazua', finalExam: 75, grade: 'C' },
    { id: '95640', name: 'Patrick N. Barbar', finalExam: 90, grade: 'B' },
    { id: '98765', name: 'Princess N. Mulbah', finalExam: 80, grade: 'C' },
    { id: '100906', name: 'Priscilla G. Sombai', finalExam: 70, grade: 'C' },
    { id: '96668', name: 'Prosper M. Williams', finalExam: 75, grade: 'C' },
    { id: '98623', name: 'Ruth Z. Gonquoi', finalExam: 0, grade: 'F' },
    { id: '97423', name: 'Sarah D. Neplay', finalExam: 55, grade: 'C' },
    { id: '97313', name: 'Tetee E. Kpalleh', finalExam: 60, grade: 'C' },
    { id: '96947', name: 'Willet P. Wilson', finalExam: 75, grade: 'B' },
    { id: '98050', name: 'Winifred T. Brown', finalExam: 50, grade: 'C' },
    { id: '93156', name: 'Yassah P. Howard', finalExam: 60, grade: 'F' },
    { id: '94689', name: 'Harrington M.S. Pabai', finalExam: 80, grade: 'C' },
    { id: '98945', name: 'Etoah Dahn', finalExam: 80, grade: 'D' },
    { id: '97286', name: 'Joshua R. Fumbah', finalExam: 75, grade: 'D' },
    { id: '70734', name: 'Moses W. Jallah', finalExam: 60, grade: 'F' },
    { id: '98770', name: 'Mardea J. Judges', finalExam: 80, grade: 'D' }
  ];

  const handleSearch = () => {
    setIsLoading(true);
    setError('');
    setStudentData(null);
    setShowScore(false);

    // Simulate loading delay
    setTimeout(() => {
      const student = studentsData.find(s => s.id === studentId.trim());
      
      if (student) {
        setStudentData(student);
      } else {
        setError('Student ID not found. Please check your ID and try again.');
      }
      setIsLoading(false);
    }, 800);
  };

  const getScoreColor = (score) => {
    if (score >= 80) return 'text-green-600';
    if (score >= 70) return 'text-blue-600';
    if (score >= 60) return 'text-yellow-600';
    return 'text-red-600';
  };

  const getScoreBadge = (score) => {
    if (score >= 80) return 'bg-green-100 text-green-800';
    if (score >= 70) return 'bg-blue-100 text-blue-800';
    if (score >= 60) return 'bg-yellow-100 text-yellow-800';
    return 'bg-red-100 text-red-800';
  };

  const getPerformanceMessage = (score) => {
    if (score >= 80) return 'Excellent performance! 🎉';
    if (score >= 70) return 'Good work! 👏';
    if (score >= 60) return 'Keep improving! 📈';
    return 'Additional support recommended 📚';
  };

  return (
    <div className="min-h-screen bg-gradient-to-br from-blue-50 via-white to-indigo-50">
      {/* Header */}
      <div className="bg-white shadow-sm border-b">
        <div className="max-w-4xl mx-auto px-4 py-6">
          <div className="flex items-center space-x-3">
            <BookOpen className="h-8 w-8 text-blue-600" />
            <div>
              <h1 className="text-2xl font-bold text-gray-900">Student Portal</h1>
              <p className="text-gray-600">Final Exam Results</p>
            </div>
          </div>
        </div>
      </div>

      <div className="max-w-4xl mx-auto px-4 py-8">
        {/* Search Section */}
        <div className="bg-white rounded-xl shadow-lg p-6 mb-8">
          <div className="flex items-center space-x-2 mb-4">
            <Lock className="h-5 w-5 text-blue-600" />
            <h2 className="text-xl font-semibold text-gray-900">Secure Access</h2>
          </div>
          
          <p className="text-gray-600 mb-6">Enter your Student ID to view your final exam score</p>
          
          <div className="flex space-x-4">
            <div className="flex-1">
              <label className="block text-sm font-medium text-gray-700 mb-2">
                Student ID Number
              </label>
              <input
                type="text"
                value={studentId}
                onChange={(e) => setStudentId(e.target.value)}
                placeholder="Enter your ID (e.g., 97908)"
                className="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent"
                onKeyPress={(e) => e.key === 'Enter' && handleSearch()}
              />
            </div>
            <div className="flex items-end">
              <button
                onClick={handleSearch}
                disabled={!studentId.trim() || isLoading}
                className="px-6 py-3 bg-blue-600 text-white rounded-lg hover:bg-blue-700 disabled:opacity-50 disabled:cursor-not-allowed flex items-center space-x-2 transition-colors"
              >
                {isLoading ? (
                  <div className="animate-spin h-4 w-4 border-2 border-white border-t-transparent rounded-full"></div>
                ) : (
                  <Search className="h-4 w-4" />
                )}
                <span>{isLoading ? 'Searching...' : 'Search'}</span>
              </button>
            </div>
          </div>
        </div>

        {/* Error Message */}
        {error && (
          <div className="bg-red-50 border border-red-200 rounded-lg p-4 mb-6">
            <div className="flex items-center space-x-2">
              <div className="h-4 w-4 bg-red-400 rounded-full"></div>
              <p className="text-red-700">{error}</p>
            </div>
          </div>
        )}

        {/* Student Results */}
        {studentData && (
          <div className="bg-white rounded-xl shadow-lg overflow-hidden">
            {/* Student Header */}
            <div className="bg-gradient-to-r from-blue-600 to-indigo-600 px-6 py-4">
              <div className="flex items-center space-x-3 text-white">
                <User className="h-6 w-6" />
                <div>
                  <h3 className="text-xl font-semibold">{studentData.name}</h3>
                  <p className="text-blue-100">ID: {studentData.id}</p>
                </div>
              </div>
            </div>

            {/* Score Section */}
            <div className="p-6">
              <div className="flex items-center justify-between mb-4">
                <h4 className="text-lg font-medium text-gray-900">Final Exam Score</h4>
                <button
                  onClick={() => setShowScore(!showScore)}
                  className="flex items-center space-x-2 px-3 py-1 bg-gray-100 rounded-full hover:bg-gray-200 transition-colors"
                >
                  {showScore ? <EyeOff className="h-4 w-4" /> : <Eye className="h-4 w-4" />}
                  <span className="text-sm">{showScore ? 'Hide' : 'Show'} Score</span>
                </button>
              </div>

              {showScore ? (
                <div className="space-y-4">
                  <div className="text-center py-8">
                    <div className={`text-6xl font-bold ${getScoreColor(studentData.finalExam)} mb-2`}>
                      {studentData.finalExam}
                    </div>
                    <div className="text-gray-500 text-lg mb-4">out of 100 points</div>
                    <div className={`inline-block px-4 py-2 rounded-full ${getScoreBadge(studentData.finalExam)} font-medium`}>
                      Overall Grade: {studentData.grade}
                    </div>
                  </div>

                  <div className="border-t pt-4">
                    <div className="text-center">
                      <p className="text-lg text-gray-700 mb-2">
                        {getPerformanceMessage(studentData.finalExam)}
                      </p>
                      
                      {/* Performance Bar */}
                      <div className="w-full bg-gray-200 rounded-full h-3 mb-4">
                        <div 
                          className={`h-3 rounded-full transition-all duration-1000 ${
                            studentData.finalExam >= 80 ? 'bg-green-500' :
                            studentData.finalExam >= 70 ? 'bg-blue-500' :
                            studentData.finalExam >= 60 ? 'bg-yellow-500' : 'bg-red-500'
                          }`}
                          style={{ width: `${studentData.finalExam}%` }}
                        ></div>
                      </div>
                      
                      <div className="text-sm text-gray-500">
                        Performance: {studentData.finalExam}%
                      </div>
                    </div>
                  </div>
                </div>
              ) : (
                <div className="text-center py-12 text-gray-500">
                  <Lock className="h-12 w-12 mx-auto mb-4 opacity-50" />
                  <p>Click "Show Score" to view your final exam result</p>
                </div>
              )}
            </div>
          </div>
        )}

        {/* Help Section */}
        <div className="mt-8 bg-blue-50 rounded-lg p-4">
          <h4 className="font-medium text-blue-900 mb-2">Need Help?</h4>
          <p className="text-blue-700 text-sm">
            If you can't find your ID or have questions about your score, please contact your instructor or the academic office.
          </p>
        </div>
      </div>
    </div>
  );
};

export default StudentDashboard;
