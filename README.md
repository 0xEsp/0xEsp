// AboutManuController.swift

import Manu

class About: Me {
    @objc func getLanguages() {
          return [
                "Swift",
                "SwiftUI",
                "Vapor",
                "Flutter",
                "Kotlin"
          ]
    }
    
    @objc func getExperiences() {
          return [
                "iOS Developer",
                "Flutter Developer",
                "Android Developer",
                "Backend Developer" (Vapor)
          ]
    }
    
    let interest = ["Hackathons", "Competitive Programming", "Apple Ecosystem", "Any Tech Stuff :)"]
}
