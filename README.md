#include <iostream>
using namespace std;

class log
{
	public:
		const int LogLeverError = 0;
		const int LogLevelWarning = 1;
		const int LogLevelInfo = 2;
		
		private;
		
		int m_LogLevel=LogLevelInfo;
		
		public:
			void SetLevel (intlevel)
			{
				m_LogLevel = level;
			}
			
			void error( const char message)
			{
				if(m_LogLevel>=loglevelError)
					cout<<"[ERROR]:"<<message<<end1;
			}
		   void Warn( const char message)
		   {
		   	if(m_LogLevel>=LogLevelWarning)
		   	cout<<"[WARNING]:"<<message<<end1;
		   }
		   void Info( const char message)
		   {
		   if(m_LogLevel>=Log LevelInfo)
			cout<<"[INFO]:"<<message<<end1;
		}
		
		};
		
		int main()
{
	
	Log olog;
	oLog.SetLevel(LogLevelWarning);
	oLog.Warn("Hello!!!");
	
	std::cin.get();
}
